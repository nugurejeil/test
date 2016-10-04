# test

```js
var me = "Hanjaehyun"

function myName(who){

  console.log(who);
  
}

myName(me);
```


```html
<!DOCTYPE html>
<html lang="ko-KR">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <title></title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="">
  <meta name="keywords" content="">
  <meta name="author" content="">
</head>
<body>
  
</body>
</html>
```


```css{
    .box{
  position:relative;
  width: 300px;
  height: 70px;
  background: yellow;

}

.box::after{
  content:'';
  position: absolute;
  top: 90%;
  right: 100%;
  bottom: 0;
  left: 0;
  background: red;
  transition: 0.4s;
}
  }

```
