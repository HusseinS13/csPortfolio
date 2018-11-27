# csPortfolio

<details>
  <summary>Webpage</summary>
    https://husseins13.github.io/testWeb/dogPage/.
      
A source of pride in the development of this project was being able to explore both HTML and CSS for the first time. I learned how to manipulate both images and texts within these languages. Nothing in the creation of this webpage was particularly difficult, but I did learn how to make an image opaque when the mouse hovers over it. Here is a snippet of that code:

    <div class="w3-container">
        <img src="group.jpg" id="cent" class="w3-opacity w3-hover-opacity-off" alt="Norway" style="width:50%">
        <h3> To kick off the day, students met with Governor Dayton to share their vision for the future of Minnesota. </h3>
        <img src="dayton.jpg" id="cent" class="w3-opacity w3-hover-opacity-off" alt="Norway" style="width:50%">
    </div>
    
  </details>
      <details>
  <summary>AutoZone Lighting in Java </summary>
  https://husseins13.github.io/lightning2/
  
A source of pride in the development of this project was being able to revisit the mousePressed() method and utilize a lot of randomly generated variables. I created the random lightning strikes by creating a while loop that randomly generated ints for the x and y variables. A challenge that I encountered, but later figured out, was how to randomly generate a background color each time the mouse was pressed. Here is the sample of my code that randomly generated ints:
  
  ```Java
void draw() {
    background(255);
    while (endX < 300) {
        endX = startX + (int)(Math.random() * 19) - 9;
        endY = startY + (int)((Math.random() * 10));
        line(startX, startY, endX, endY);
        startX = endX;
        startY = endY;
    }
    while (end2X < 300) {
        end2X = start2X + (int)(Math.random() * 19) - 9;
        end2Y = start2Y + (int)((Math.random() * 10));
        line(start2X, start2Y, end2X, end2Y);
        start2X = end2X;
        start2Y = end2Y;
    }
}

```
  </details>
<details>
  <summary>AutoZone Lightning in JavaScript</summary>
  https://husseins13.github.io/lightning2/jsacs_lightning/
  
A source of pride in the development of this code, was being able to explore JavaScript for the first time. I learned about some of the similarities and differences between Java and JavaScript. I was able to rewrite parts of my code so that it would have the same functionality as the Java version. Through exploration, I learned how to create a random background color that is constantly changing, butI struggled to make the colors change with the mousePressed() method.
  </details>


<details>
  <summary>Dice Roll </summary>
    https://husseins13.github.io/dice3/

    A source of pride in the development of this code was being able to create all of the Dice objects and have them each display a different number everytime the mouse was pressed. A challenge that I encountered when writing this code was being able to randomly generate a different type of die for each object. I solved this issue by creating a roll() method that randomly generated an int from 1-6. This int was then used to create a die with the corresponding value. Here is a snippet of that code:
  
  ```Java
   void roll(){ // ur code here
  m = (int)(Math.random()*6)+1;
  }
  void show()  {
     fill(#BDBDBD);
    rect(x, y, 50, 50);
    if (m == 1) {
      noStroke();
      fill(#FF9700 );
      ellipse( x+25, y+25, 6, 6);
    }
    if ( m == 2) { 
      fill (#E8CA53); 
      noStroke();
      ellipse( x+16, y+25, 6, 6); 
      ellipse( x+32, y+25, 6, 6);
  }
  ...
  }
  
  ```
    
   </details>
    
<details>
  <summary>Computer Science at MIT </summary>
  https://docs.google.com/presentation/d/e/2PACX-1vSr-_JrrET3n5xBaLSEZix7rZ2E2e36VktTxQe9m339OE6w0e5tl992_AbKmIOQKuY9DkCQBhBwAzbo/pub?start=true&loop=true&delayms=10000)
  </details>
  
* Chemotaxis [here](https://husseins13.github.io/chemotaxis4/)

```Java
   void follow()
   {
     if (followMouse == true && get(bacX,bacY) != color(0,255,0))
     {
       if(bacX > mouseX){
         bacX = bacX + (int)(Math.random()*(-5)+1);
       }else {
         bacX = bacX + (int)(Math.random()*(5)-1);
       }
       if(bacY > mouseY){
         bacY = bacY + (int)(Math.random()*(-5)+1);
       }else {
         bacY = bacY + (int)(Math.random()*(5)-1);
       }  
     }
     if(followMouse == true && get(bacX,bacY) == color(0,255,0))
     {
       followMouse = false;
     }

   }
   ```
*Starfield [here](https://husseins13.github.io/starfield5/)

```Java
  void star(float x, float y, float radius1, float radius2, int npoints)
  {
    float angle = TWO_PI / npoints;
    float halfAngle = angle/2.0;
    beginShape();
    for (float a = 0; a < TWO_PI; a += angle) {
      float sx = x + cos(a) * radius2;
      float sy = y + sin(a) * radius2;
      vertex(sx, sy);
      sx = x + cos(a+halfAngle) * radius1;
      sy = y + sin(a+halfAngle) * radius1;
      vertex(sx, sy);
    }
    endShape(CLOSE);
  }
}
```
