function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(255, 255, 255);
  noStroke();
  fill(255, 240, 204);
  rect(0, 0, 400, 400);
  fill(255, 222, 52);
  ellipse(200, 200, 200, 200);
  //face
  fill(204, 255, 255);
  rect(130, 220, 140, 50);
  //mask
  stroke(0);
  line(93, 188, 130, 220);
  line(93, 189, 130, 270);
  //left_mask_lines
  line(270, 220, 307, 188);
  line(270, 270, 307, 189);
  //right_mask_lines
  line(130, 230, 270, 230);
  line(130, 240, 270, 240);
  line(130, 250, 270, 250);
  line(130, 260, 270, 260);
  //lines_on_mask
  stroke(51, 25, 0);
  strokeWeight(4);
  fill(255, 222, 52);
  rect(130, 170, 50, 30);
  //left_spec
  line(102, 177, 130, 179);
  //left_line
  rect(220, 170, 50, 30);
  //right_spec
  line(270, 179, 298, 177);
  //right_line
  line(180, 180, 220, 180);
  //mid_line
  stroke(0);
  strokeWeight(1);
  fill(64, 64, 64);
  ellipse(160, 185, 15, 10);
  //left_eye
  ellipse(240, 185, 15, 10);
  //right_eye
  fill(255, 255, 255);
  ellipse(100, 185, 14, 14);
  rect(93, 185, 7, 17);
  //left_earplug
  ellipse(300, 185, 14, 14);
  rect(300, 185, 7, 17);
  //right_earplug
}
