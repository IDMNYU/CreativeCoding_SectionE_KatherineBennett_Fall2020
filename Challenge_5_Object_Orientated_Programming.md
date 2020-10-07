Challenge 5: Object Orientated Programming

Take EITHER the sketch below OR someone else's (ie. not your nor your partner's) Creature from class.

Translate it to Object Orientated Programming, creating a class which can create multiple versions of this creature. You must use a constructor function. Once you have done that much, keep transforming and developing the class. For example: create different methods for various things such as display and movement.

Then, in the main sketch, make more than one of these creatures. Each of these creatures must be a bit different from the last. (Think: color, size, motion etc.)

You may do this in either P5.js or Processing.



***********

//https://www.openprocessing.org/sketch/753020
// Sketch by Jack Zhang

void setup() {
  size(500, 500);
  background(#D4CD8C);
}
//arms
void draw() {
  fill(0);
  ellipse(370, 350, 50, 50);
  fill(#D1E8E3);
  ellipse(370, 350, 10, 10);
  ellipse(175, 220, 50, 45);
  ellipse(325, 220, 50, 45);
  fill(#D4B48C);
  rect(120, 190, 20, 90);
  rect(125, 280, 10, 70);
  rect(360, 190, 20, 90);
  rect(365, 280, 10, 70);

  //shoulders
  quad(120, 190, 120, 230, 110, 220, 100, 200);
  quad(380, 190, 380, 230, 390, 220, 400, 200);

  //body
  line(125, 350, 110, 370);
  line(135, 350, 150, 370);
  line(110, 370, 110, 390);
  line(150, 370, 150, 390);

  fill(#CCC8DC);
  ellipse(250, 170, 150, 150);
  fill(#908E9C);
  rect(170, 190, 160, 90);
  rect(160, 290, 180, 110);
  line(175, 280, 250, 290);
  line(325, 280, 250, 290);
  line(170, 240, 330, 240);
  line(160, 300, 340, 350);

  fill(#4FDBBF);
  rect(190, 320, 5, 10);
  rect(320, 220, 5, 10);
  rect(300, 220, 5, 10);
  ellipse(220, 140, 15, 15);
  ellipse(280, 140, 15, 15);
  fill(#AD035C);
  ellipse(200, 240, 10, 10);
  point(230, 340);
  point(240, 340);
  point(230, 350);
  point(240, 350);

  //feet
  fill(#124F6B);
  triangle(190, 400, 230, 400, 210, 450);
  triangle(310, 400, 270, 400, 290, 450);

  //emotion_1
  /*
triangle(235, 180, 265, 180, 250, 160);
   */

  //emotion_2
  /*
rect(230, 170, 40, 5);
   */
}
************