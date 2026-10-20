# 10.20

function setup() {
  createCanvas(800, 600);
}

function draw() {
  background(255);

  fill(20);
  noStroke();
  textAlign(CENTER, CENTER);
  textSize(22);
  text("THE MACHINE SEES ME", width / 2, 70);

  stroke(30);
  strokeWeight(1);
  noFill();
  rect(100, 130, 600, 350);

  noStroke();
  fill(100);
  textSize(14);
  text("CAMERA SYSTEM / WAITING", width / 2, 520);
}
