complexShape
============
//complex shape

void setup(){
  size(400,400);
  smooth();
  background(0, 0, 0);
}

void draw(){
  //draw rectangles
  fill(#ffff33, 80);
  stroke(120);
  strokeWeight(10);
  rectMode(CENTER);
  rect(width/2, height/2, 310, 310);
  
  //draw the ellipse
  noStroke();
  fill(102, 204, 255);
  ellipse(width/2, height/2, 300, 300);
  
  //draw the triangles
  noStroke();
  fill(255, 255, 255, 80);
  triangle(200, 50, 310, 300, 90, 300);
  
}