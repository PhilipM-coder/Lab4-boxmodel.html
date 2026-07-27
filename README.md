<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CSS Box Model Lab</title>
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  padding: 20px;
}

.box {
  width: 300px;
  height: 150px;
  border: 5px solid blue;
  padding: 20px;
  margin: 20px;
  background-color: #f0f0f0;
}
</style>
</head>
<body>

<h1>CSS Box Model Lab</h1>

<div class="box">
<p>This is a demonstration of the CSS Box Model.</p>
</div>

<div class="box">
<p>This is a second box demonstrating how top and bottom margins push adjacent elements apart.</p>
</div>

</body>
</html>
