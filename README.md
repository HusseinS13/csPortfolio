# csPortfolio

<details>
  <summary> My Webpage[here]( https://husseins13.github.io/testWeb/dogPage/).</summary>
    https://husseins13.github.io/testWeb/dogPage/.
      
A source of pride in the development of this project was being able to explore both HTML and CSS for the first time. I learned how to manipulate both images and texts within these languages. Nothing in the creation of this webpage was particularly difficult, but I did learn how to make an image opaque when the mouse hovers over it. Here is a snippet of that code:

    <div class="w3-container">
        <img src="group.jpg" id="cent" class="w3-opacity w3-hover-opacity-off" alt="Norway" style="width:50%">
        <h3> To kick off the day, students met with Governor Dayton to share their vision for the future of Minnesota. </h3>
        <img src="dayton.jpg" id="cent" class="w3-opacity w3-hover-opacity-off" alt="Norway" style="width:50%">
    </div>
    
  </details>
      
      
* AutoZone Lighting! Java [here](https://husseins13.github.io/lightning2/)
* AutoZone Lightning JS [here](https://husseins13.github.io/lightning2/jsacs_lightning/)

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
* Dice Roll [here](https://husseins13.github.io/dice3/)
* Computer Science at MIT [here](https://docs.google.com/presentation/d/e/2PACX-1vSr-_JrrET3n5xBaLSEZix7rZ2E2e36VktTxQe9m339OE6w0e5tl992_AbKmIOQKuY9DkCQBhBwAzbo/pub?start=true&loop=true&delayms=10000)
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
