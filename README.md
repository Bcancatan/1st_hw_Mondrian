# 1st_hw_Mondrian
void setup () {
  // set window size
  size(700, 700);
}

void draw () {
  background(#D8DE48);
  fill(#B9222C);
  rect(0, 90, 100, 200);
  fill(#B96D09);
  rect(100, 200, 100, 200);
  fill(#DE8484);
  rect(200, 300, 100, 200);
  
  strokeWeight(5);
  stroke(#F5EDEF);
  fill(#CB5327);
  ellipse(450, 350, 100, 100);
  fill(#32E51C);
  ellipse(500, 300, 100, 100);
  fill(#D8B939);
  ellipse(550, 250, 100, 100);
  fill(#4F9B9D);
  ellipse(600, 200, 100, 100);
  fill(#4D4709);
  ellipse(650, 150, 100, 100);
  
  strokeWeight(8);
  stroke(#3A1BBC);
  quad(438, 431, 486, 420, 469, 463, 430, 476); 
  quad(538, 531, 586, 520, 569, 563, 530, 576); 
  fill(#1DB45B);
  triangle(330, 375, 358, 320, 386, 375);
  fill(#F9FA03);
  triangle(230, 275, 258, 220, 286, 275);
  fill(#AFAF3A);
  triangle(130, 175, 158, 120, 186, 175);
  fill(#484836);
  triangle(25, 70, 53, 15, 81, 70);

  // line(90,75,90,300); yerlesim duzenini anlayamadim

  line(625, 575, 575, 575);
  line(650, 600, 600, 600);
  line(675, 625, 625, 625);
  line(700, 650, 650, 650);
  strokeWeight(5);
  stroke(#050505);
  fill(#35CB70);
  rect(300, 400, 100, 200);
  fill(#09B5B9);
  rect(400, 500, 100, 200);
  fill(#095534);
  rect(50, 600, 100, 50);
  fill(#552609);
  rect(50, 650, 50, 100);
  fill(#E5905A);
  rect(100, 650, 150, 50);
  fill(#2BDED3);
  rect(100, 600, 50, 150);
  fill(#FF150D);
  rect(100, 600, 150, 50);
  fill(#1129F0);
  //rotate(radians(45)); sekili asagiya dogru surukluyor?
  rect(500, 0, 200, 80);
  fill(#B02EF2);
  rect(300,0,200,80);
  fill(#AA0728);
  rect(100,0,200,80);
  fill(#0DFF7B);
  rect(300,90,200,80);
  fill(#A73643);
  rect(350,190,100,60);
  
}
