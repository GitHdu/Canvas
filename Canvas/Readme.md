Canvas
HTML

<canvas id="canvas" style="margin:50px auto;border:1px solid #ccc;display:block"></canvas>
JavaSrcipt

var canvas=document.getElementById("canvas");
var context=canvas.getContext("2d");
Draw more Lines

context.beginPath();
context.closePath()
Draw

context.fillStyle="#ccc";//填充
context.strokeStyle="#ccc";//描边
context.fill();
context.stroke();
