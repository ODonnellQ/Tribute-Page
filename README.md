# Tribute-Page

background(219, 255, 255);



fill(255, 255, 255);
rect(60, 150, 280, 207);
for (var t = 5; t < 12.1; t++) {
    for (var r = 1.7; r < 9; r++) {
        image(getImage("cute/RampSouth"), r*35, t*26, 36, 60);
    }
}
fill(174, 180, 214);
triangle(200, 28, 350, 150, 50, 150);
fill(250, 45, 45);
rect(180, 280, 40, 77);
fill(0, 0, 0);
ellipse(214,320,7,7);

for (var j = 0.22; j < 2.5; j++) {
    for (var i = 1; i < 9.4; i++) {
        image(getImage("cute/BrownBlock"), i*36, j*40, 40, 60);
    }
}


fill(219, 255, 255);
noStroke();
triangle(2000, 30, 351, 150, 192, 22);
triangle(29, -14, 207, 23, 33, 162);

for (var q = 4.23; q < 4.3; q++) {
    for (var w = 2.0; w < 5.8; w++) {
        image(getImage("cute/WindowTall"), w*51, q*39, 39, 83);
    }
}

for (var t = 3; t < 3.5; t++) {
    for (var r = 1.7; r < 9; r++) {
        image(getImage("cute/RampSouth"), r*35, t*50, 36, 60);
    }
}
stroke(7, 186, 19);
for(var g= 0; g<=400; g+=1.199){
    fill(34, 176, 12);
 line(1+g,400,1+g,362);   
}

image(getImage("cute/TreeShort"), 3,298 , 60, 100);
image(getImage("cute/TreeShort"), 341,298 , 60, 100);

image(getImage("cute/DirtBlock"), -34, 252, 450, 450);
