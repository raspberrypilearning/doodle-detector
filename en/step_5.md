## Create a canvas

<html>
  <div style="position: relative; overflow: hidden; padding-top: 56.25%;">
    <iframe style="position: absolute; top: 0; left: 0; right: 0; width: 100%; height: 100%; border: none;" src="https://www.youtube.com/embed/ZvoB6199Qj0?rel=0&cc_load_policy=1" allowfullscreen allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"></iframe>
  </div>
</html>


Now that your model can distinguish between drawings, you can use it in a Scratch program.

--- task ---
+ Click on the **< Back to project** link.

+ Click on **Make**.

+ Click on **Scratch 3**.

+ Click on **Open in Scratch 3**.

--- /task ---

Machine Learning for Kids has added some special blocks to Scratch to allow you to use the model you just trained. Find them at the bottom of the blocks list.

![New blocks called 'Doodle detector' appear in the menu under Images](images/new-blocks.png)

--- task ---

+ Create a new sprite using the 'Paint' option. Name your sprite 'Canvas'.
![Add a new sprite using paint, and name it canvas](images/new-sprite.png)

--- /task ---

--- task ---
+ Click the purple **Convert to bitmap** button at the bottom, underneath the drawing area.
--- /task ---


--- task ---
+ Click on the **Code tab** for the canvas sprite and create two **variables** called `result` and `confidence`.

![Create two new variables called confidence and result](images/create-variable.png)

--- /task ---

--- task ---
+ Drag in the correct blocks to set the value of these variables when the space key is pressed. Create a **broadcast** called `detected` and broadcast it once the variables are set.

![Scratch code: When space key pressed, set result to recognise image (costume image) label, set confidence to recognise image (costume image) confidence, broadcast detected](images/canvas-sprite.png)

--- /task ---

