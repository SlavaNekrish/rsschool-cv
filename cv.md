![Линия](img/Line.png)

# Viachaslau Nekrysh

### Intern, Junior frontend developer

### CONTACT INFORMATION

- Minsk
- +375 (25) 615-07-86
- [vnekrish@mail.ru](mailto:vnekrish@mail.ru)
- Linkedin: [https://www.linkedin.com/in/viachaslau-nekrysh-8a0946254](https://www.linkedin.com/in/viachaslau-nekrysh-8a0946254)
- Telegram: @vjachaslau
- Skype: vjachaslau1

### BRIEF SELF-INTRODUCTION

_As a relay protection technical engineer with 14 years background, I am attentive_
_to details, interested in solving problems and good team player. I am full of energy_
_and ready to study new technologies the company works with. I am really into this_
_field, watching tech content, reading web development books._
_I believe, that my ability to learn and to gain new skills will lead me through this path of becoming a proficient Frontend Developer._

### SKILLS

![Skills](images/Skills.png)

### CODE

```javascript
function withRainbowFrame(colors) {
  return function (Comp) {
    return (props) => {
      const reduceCB = (acc, cur) => {
        return <div style={{ border: 'solid 5px ' + cur, padding: '5px' }}>{acc}</div>;
      };
      const rainbowFrame = colors.reduce(reduceCB, <Comp {...props} />);
      return <div style={{ width: 600, textAlign: 'center', margin: 'auto' }}>{rainbowFrame}</div>;
    };
  };
}
```
