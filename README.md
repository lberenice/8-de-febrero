# 8-de-febrero
function setup() {

createCanvas(400, 400);

background(100);

var num;

}

function draw() {

var num;

if (mouseIsPressed) {

num = int(random(0, 7))
  

if (num == 1) {

uno()

}

if (num == 2) {

dos()

}

if (num == 3) {

tres()

}

if (num == 4) {

cuatro()

}

if (num == 5) {

cinco()

}

if (num == 6) {

seis()

}

}

}

function uno()

{

fill(255);

rect(100, 100, 200, 200);

fill(0);

ellipse(200, 200, 20)

}

function dos() {

fill(255);

rect(100, 100, 200, 200);

fill(0);

ellipse(225, 200, 20)

ellipse(175, 200, 20)

}

function tres() {

fill(255);

rect(100, 100, 200, 200);

fill(0);

ellipse(200, 200, 20)

ellipse(150, 200, 20)

ellipse(250, 200, 20)

}

function cuatro() {

fill(255);

rect(100, 100, 200, 200);

fill(0);

ellipse(150, 150, 20)

ellipse(250, 150, 20)

ellipse(150, 250, 20)

ellipse(250, 250, 20)

}

function cinco() {

fill(255);

rect(100, 100, 200, 200);

fill(0);

ellipse(200, 200, 20)

ellipse(150, 150, 20)

ellipse(250, 150, 20)

ellipse(150, 250, 20)

ellipse(250, 250, 20)

}

function seis() {

fill(255);

rect(100, 100, 200, 200);

fill(0);

ellipse(150, 150, 20)

ellipse(250, 150, 20)

ellipse(150, 250, 20)

ellipse(250, 250, 20)

ellipse(200, 150, 20)

ellipse(200, 250, 20)

}
