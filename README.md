# COLOR A PEGASUS 

## Codecademy Phaser JS Lesson

In this lesson we’re going to provide functionality to make our first coloring-book game called Color a Pegasus.

_In this lesson we’re going to build:_
* Click events for the pegasus body to color in each section with a new color.
* Click events for the palette to update the current color choice.
* Hover events for the pegasus body to indicate the part of the pegasus to be clicked.
* Hover events for the palette to show when a color is being selected (and to indicate which color is selected).
  
### Coloring

We’ve been given the basic layout of our Game — it’s up to us, the game developer, to provide the part of our game
that makes it playable. We need to create the mechanics of the game, the part that makes it more than a picture of a pegasus.

### Updating Color

Now that we can change the color of our pegasus, let’s get to work on making that palette selector functional. 
When we click on a color, we want that to become the selected color.

### Indicating Selections

Coloring the pegasus is great, the “playing” aspect of our game is figured out, but we need to consider our presentation. If we want someone playing our game to know where to click and how to actually color in the pegasus, we’re going to need to work on the interface.
You may have noticed that clicking on some parts of the pegasus don’t perfectly line up with the shapes. This has to do with how the shapes are stacked on top of each other. There’s a lot of ways to fix that potentially, but a solution that will work well is giving the person playing the game some insight into what part of the Pegasus will be colored after they click.
We’re going to use the screen blend mode to indicate which part of the Pegasus is going to be selected. Blend modes dictate how a filled-in shape interacts with the other shapes visible, somewhat like changing the opacity and color of the shape. The result will be that our highlighted section will turn semi-transparent and white with a white outline.

<img width="331" alt="Снимок экрана 2023-10-24 в 01 34 03" src="https://github.com/mtapirina/color_a_pegasus/assets/116927372/35d31bfc-8288-46c5-b3f0-f53b7d9f06f3">

### Indicating Palette Selection

Our game is a lot more playable now that people know what they’re clicking on, but how can we keep track of what color is currently active? By adding relevant hover events to our paletteCircles!

Congratulations! You made your first game, Color a Pegasus! Over the course of this lesson you created the sequence of event handlers to:
* Own and update the state of the game.
* Update the color of specific parts of the pegasus in the game
* Highlight GameObjects to indicate what will be clicked on
You’ve displayed a lot of control over the possible mouse cursor events and successfully used that control to build a coloring game!

### Extra:

* Add a new color to the palette.
* Color in the background as well as the pegasus.
  
<img width="511" alt="Снимок экрана 2023-10-24 в 15 08 16" src="https://github.com/mtapirina/color_a_pegasus/assets/116927372/e5c4b665-c68a-4729-9dfa-1053aece4686">
