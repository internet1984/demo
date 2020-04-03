<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title>灰色图像滤镜 grayscale</title>
    <style>
     img,div{
        filter: grayscale(100%); 
      }
      div{
        width: 300px;
        height: 300px;
        background-repeat: no-repeat;
      }
      .original{
        filter: none!important; 
      }
    </style>
  </head>
  <body>
<h1>原图</h1>
    <img class="original" src="https://www.youmeitu.com/Upload/20200312/1583987657801952.jpg"/><hr/>
    <h1>img </h1>
    <p>filter: grayscale(100%); </p>
<img src="https://www.youmeitu.com/Upload/20200312/1583987657801952.jpg"/><hr/>
<h1>background</h1>
<p>filter: grayscale(100%); </p>
<div  style="background-image: url(https://www.youmeitu.com/Upload/20200312/1583987657801952.jpg);"></div>

<p>filter: grayscale(50%); </p>
<div  style="filter: grayscale(50%);background-image: url(https://www.youmeitu.com/Upload/20200312/1583987657801952.jpg);"></div>

<p>filter: grayscale(80%); </p>
<div  style="filter: grayscale(80%);background-image: url(https://www.youmeitu.com/Upload/20200312/1583987657801952.jpg);"></div>


  </body>
</html>
