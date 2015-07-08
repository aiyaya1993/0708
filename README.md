# 0708
css的伪类
<!DOCTYPE html>
<html>
 <head>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <meta name="author" content="aiyaya">
  <title>未命名</title>
  <style type="text/css">
   *{margin: 0; padding: 0;}
   .box{width: 100%; height: 100px;background-color: green;}
   .item{float: left;height:80px;font-size:20px; background-color: white;margin-top:10px; }
   .item:first-child {width: 200px;margin: 10px;}
   .item:last-child{ width:100px; background:gray;margin:10px;}
  </style>
 </head>
  <body>
  <div class="box">
    <div class="item">column 1</div>
    <div class="item">column 2</div>
    <div class="item">column 3</div>
  </div>
  </body>
  </html>
