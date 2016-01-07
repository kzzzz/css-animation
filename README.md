# CSS animation

## Tools
- [css3 please](http://css3please.com/)
- [css3generator](http://css3generator.com/)
- [ceaser CSS easing animation tool](http://matthewlein.com/ceaser/)
- [cubic-bezier](http://cubic-bezier.com/)
- [animate.css](https://daneden.github.io/animate.css/)
- [animatable](http://leaverou.github.io/animatable/)

## animation-fill-mode
- forwards
- backwards
- both

## animation-direction
- normal
- reverse
- alternate
- alternate-reverse

## animation-timing-function
- predefined keywords
  - ease/linear/ease-in/ease-out/ease-in-out
- cubic Bézier curves
- steps

## shorthands

```css
.my-div{
  animation-name: bounce-in;
  animation-duration: 4s;
  animation-timing-function: ease-in;
  animation-iteration-count: 2;
  animation-direction: alternate;
  animation-fill-mode: forwards/backwards/both;

  animation: bounce-in 1s ease-in 2 alternate forwards;
}
```
