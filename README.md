# java-lec.19

<!doctype html>
<html>
<head>
  <title>WEB1 - JavaScript</title>
  <meta charset="utf-8">
</head>
<body>
  <h1><a href="index.html">WEB</a></h1>
  <input type="button" value="night" onclick="
  if(this.value === 'night') {
    document.querySelector('body').style.backgroundColor = 'black';
    document.querySelector('body').style.color = 'white';
    this.value = 'day';
  } else {
    document.querySelector('body').style.backgroundColor = 'white';
    document.querySelector('body').style.color = 'black';
    this.value = 'night';
  }
  ">
  <ol>
    <li><a href="1.html">HTML</a></li>
    <li><a href="2.html">CSS</a></li>
    <li><a href="3.html">JavaScript</a></li>
  </ol>
  <h2>JavaScript</h2>
  <p>자바스크립트 관련 내용
  </p>

  <input type="button" value="night" onclick="
   var target = document.querySelector('body');
  if(this.value === 'night') {
    target.style.backgroundColor = 'black';
    target.style.color = 'white';
    this.value = 'day';
  } else {
    target.style.backgroundColor = 'white';
    target.style.color = 'black';
    this.value = 'night';
  }
">
</body>
</html>
