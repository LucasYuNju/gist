# gist

```
const canvas = document.getElementById('anti-alias');
const ctx = canvas.getContext('2d');
ctx.beginPath();
ctx.moveTo(80, 50);
ctx.lineTo(100, 50);
ctx.lineTo(50, 100);
ctx.closePath();
ctx.fillStyle = '#0000ff';
ctx.strokeStyle = '#0000ff';
ctx.strokeWidth = 2;
ctx.fill();
ctx.stroke();
```
