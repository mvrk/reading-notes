

## Transforms

The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

- Transform Syntax
```
div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}
```


## CSS Transitions & Animations

Transitions provide a change from one state to another, while animations can set multiple points of transition upon different keyframes.
here are four transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay. Not all of these are required to build a transition, with the first three are the most popular.

```
.box {
  background: #2db34a;
  transition-property: background;
  transition-duration: 1s;
  transition-timing-function: linear;
}
.box:hover {
  background: #ff7b29;
}
```

- transition property
```html
background-color
background-position
border-color
border-width
border-spacing
bottom
clip
color
crop
font-size
font-weight
height
left
letter-spacing
line-height
margin
max-height
max-width
min-height
min-widthopacity
outline-color
outline-offset
outline-width
padding
right
text-indent
text-shadow
top
vertical-align
visibility
width
word-spacing
z-index
```

- transition duration

```
.box {
  background: #2db34a;
  border-radius: 6px;
  transition-property: background, border-radius;
  transition-duration: .2s, 1s;
  transition-timing-function: linear;
}
.box:hover {
  background: #ff7b29;
  border-radius: 50%;
}
```