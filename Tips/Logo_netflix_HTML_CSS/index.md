## O HTML
```HTML
<div class="netflix"></div>
```

## O CSS
```css
body {
  display: flex;
  align-items: center;
  height: 100vh;
  margin: 0;
  background: black;
}

.netflix {
  width: 140px;
  height: 250px;
  margin-left: 50%;
  position: relative;
  transform: translateX(-50%);
  background: linear-gradient(
     90deg,
     #b1060e 0,
     #b1060e 50px,
     transparent 50px,
     transparent 90px,
     #b1060e 90px,
     #b1060e 140px
    );
}

.netflix::before
.netflix::after {
  display: block;
  content: '';
  position: absolute;
}

.netflix::before {
  width: 50px;
  height: 250px;
  top: 0;
  left: 45px;
  backgrund-color: #e50914;
  transform: skewX(19.6deg);
  box-shadow: 0 0 30px black;
}

.netflix::after {
  width: 190px;
  height: 25px;
  top: 245px;
  left: -25px;
  border-radius: 50%;
  backgrund-color: black;
}
```

![](foto1.png)