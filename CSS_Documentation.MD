## CSS Documentation

<a name='top'></a>
| No | Subject |
| --- | ---------------------------------------------------------------------- |
| 1.1 | [How to use External Stylesheet?](#1.1) |
| 1.2 | [How to use internal style?](#1.2) |


<a name='1.1'></a>

### How to use External Stylesheet ?

---
- Make sure you include the correct path to your CSS file in the href
```html
//index.html
<!DOCTYPE html>
<html>
 <head>
 <meta charset="utf-8" />
 <link rel="stylesheet" type="text/css" href="style.css">
 </head>
 <body>
 <h1>Hello world!</h1>
 <p>I ♥ CSS</p>
 </body>
</html>
```

```css
//style.css
h1 {
 color: green;
 text-decoration: underline;
}
p {
 font-size: 25px;
 font-family: 'Trebuchet MS', sans-serif;
}
```

[Go to top:arrow_up: ](#top)

<a name='1.2'></a>

### How to use Internal style ?

---
- In head tag write `<style></style>`.
- In style tag write css same as external stylesheet.

```html
<head>
 <style>
 h1 {
 color: green;
 text-decoration: underline;
 }
 p {
 font-size: 25px;
 font-family: 'Trebuchet MS', sans-serif;
 }
 </style>
</head>
<body>
 <h1>Hello world!</h1>
 <p>I ♥ CSS</p>
</body>
```
[Go to top:arrow_up: ](#top)