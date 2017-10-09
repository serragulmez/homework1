# void setup(){
  // set window size
  size(600,600);
  
}
void draw(){
  background(#7379A2);
  
    // write text
  fill(#444F98);
  text("hello I'm back",15,15);
  
    // draw ellipse with mouse cord.
  strokeWeight(3);
  stroke(#C5C6CB);
  fill(#0C1B76);
  ellipse(mouseX,mouseY,100,100);
  
    // draw rectangle
  strokeWeight(9);
  stroke(#710F0F);
  fill(#F55454);
  rotate(radians(35));
  rect(300,150,150,150);
  
    //draw line
  stroke(#5966B7);
  line(mouseX,mouseY,80,75);
  
    //draw quad
  strokeWeight(6);
  stroke(#D0A2F0);
  fill(#49126F);
  quad(45,33,92,28,70,63,30,69);
  
    //draw triangle
  strokeWeight(2);
  stroke(#F5A6D5);
  fill(#FC0399);
  triangle(40,75,58,30,85,78);
  
}
