## O HTML 
```html
<div>
  <span>O</span>
  <span>V</span>
  <span>E</span>
  <span>R</span>
  <span>L</span>
  <span>A</span>
  <span>P</span>
</div>
```

## O CSS
```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
}

body {
   background-color: #1f1c32;
}

div {
   position: absolute;
   top: 50%;
   left: 50%;
   transform: translate(-50%, -50%);
   width: 100%;
   text-align: center;
   color: white;
}

div span {
   font-size: 22vw;
   font-weight: 800;
   text-shadow: -0.08em 0.03em 0.12em rgba(0, 0, 0, 0.9);
}

div span:not(:first-child) {
    margin-left: -0.23em;
}
```

![](foto1.png)