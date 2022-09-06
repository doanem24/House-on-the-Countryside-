# House-on-the-Countryside-
My first GitHub post!

size(400, 500);

strokeWeight(3);
background(200, 230, 250);
fill(230, 250, 10);
ellipse(60, 60, 60, 60); //Sun
strokeWeight(5);
stroke(0);
line(60, 25, 60, 2);  // Rays from Sun 
line(95, 60, 118, 60);
line(60, 95, 60, 118);
line(25, 60, 2, 60);
line(85, 20, 80, 28);
line(90, 38, 105, 30);
line(90, 82, 105, 90);
line(80, 95, 85, 105);
line(40, 25, 35, 15);
line(30, 38, 15, 30);
line(40, 95, 35, 100);
line(30, 82, 15, 90);

fill(160, 100, 0);
triangle(200, 20, 40, 220, 360, 220); //Roof

fill(0, 160, 0);
rect(0, 420, 400, 80); //Landscape outline

fill(250, 180, 0);
rect(80, 220, 240, 250); //House Body

fill(200, 220, 230);
ellipse(130, 280, 70, 70); // Windows
ellipse(270, 280, 70, 70);

fill(240, 180, 175);
rect(150, 330, 100, 140); // Doors

fill(200);
ellipse(170, 400, 20, 20); //Door Knob

stroke(240, 190, 80);
strokeWeight(10);
line(200, 70, 160, 120); // Attic Window
line(200, 70, 240, 120);
line(160, 120, 160, 165);
line(240, 120, 240, 165);
line(200, 110, 240, 165);
line(200, 110, 160, 165);

stroke(0);
strokeWeight(5);

noFill();
arc(200, 100, 140, 240, QUARTER_PI, PI-QUARTER_PI);
