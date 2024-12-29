

 <div>
     This is an HTML <b>element</b>.
 </div>

 <style>
     h1 {
         color: blue;
     }
 </style> 
<h1>This is a blue heading</h1>



 <script>
     function sayHello() {
         alert('Hello from JavaScript');
     }
 </script> 
<button> οnclick="sayHello()">Click me</button>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Card Layout</title>
<link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="container">
  <div class="header">
    <h1>标题</h1>
    <p>一个标题会告诉你【不对】</p>
  </div>
  <div class="card-container">
    <!-- Card 1 -->
    <div class="card">
      <img src="path_to_image" alt="Card image">
      <p>卡牌名称</p>
    </div>
    <!-- Repeat for other cards -->
  </div>
</div>
<script src="script.js"></script>
</body>
</html>



