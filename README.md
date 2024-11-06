# js-escreve1C
<!DOCTYPE html>
<html lang="en">
  <head>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.9.2/p5.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.9.2/addons/p5.sound.min.js"></script>
    <link rel="stylesheet" type="text/css" href="style.css">
    <meta charset="utf-8" />

  </head>
  <body>
    <main>
    </main>
    <script src="sketch.js"></script>
  </body>
</html>
function setup() {
  createCanvas(400, 400);
  background("white")
}

function draw() {
  stroke("blue");
  fill("red");
  
  
  if (mouseIsPressed) {
    rect(mouseX, mouseY, 20, 35);
  }
}
html, body {
  margin: 0;
  padding: 0;
}
canvas {
  display: block;
}
