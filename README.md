# csPortfolio

* MyWebPage [here](https://husseins13.github.io/testWeb/dogPage/) 
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
