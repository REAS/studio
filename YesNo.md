###YES NO 

Layers of original and appropriated instructions. 

*Stratum 1* 

Make a grid or find a grid. Do one thing or another thing inside each unit.

*Stratum 1.1* 

Draw a uniform grid of 200 x 200 squares within 1 square meter. Open a telephone directory and read the numbers in order. For each square, starting in the upper-left corner, fill with blue paint if the number is even, fill with red paint if the number is odd. 

*Stratum 1.2* 

Draw a grid of 40 x 25 units. Find a coin and define one side as A and the other as B. For each square, starting in the upper-left corner, flip the coin. If it lands with side A up, draw a line from the lower left to the upper right. If side B lands up, draw a line from the upper left to the lower right.

*Stratum 1.2.1* 

`10 PRINT CHR$(205.5+RND(1)); : GOTO 10` 

*Stratum 1.2.2* 

```size(3200, 2000);
background(255);
for (int y = 0; y < height; y += 80){
 for (int x = 0; x < width; x += 80){
  if (random(1) > 0.5) {
   line(x, y, x+80, y+80);
  } else {
   line(x, y+80, x+80, y);
  } 
 } 
}```
