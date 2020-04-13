# Snap Demo
Snap is a programming environment where developers can drag and drop blocks of code to create applications. Go to https://snap.berkeley.edu/snapsource/dev/snap.html to begin!

## Page Sections
- **Blocks:** This pane on the left is where the Snap blocks live. They can be dragged to the **Scripts** section to create code.
- **Scripts:** This central part is where the code for the program lives. Drag blocks from the **Blocks** section into this section to create code.
- **Stage:** On the top right, this is where the program will execute. This is how users interact with the developed applications.
- **Sprites:** On the bottom right, this is where all of the _sprites_ appear. A sprite is a character or object within a Snap application that can interact with the user.

## Change a costume
1. At the top of the **Scripts** area, click the **Costumes** tab
1. In Windows File Explorer, locate an image file to import as a costume (e.g., [Smile.png](Smile.png))
1. Drag and drop the file into the **Costumes** section
1. Notice the sprite change on the stage!

## Basic sprite movement
1. At the top of the **Scripts** area, click the **Scripts** tab
1. At the top of the **Blocks** section, click _Control_ to view the Control blocks
1. Find the "when {space} key pressed" block, and drag it to the **Scripts** area  
    ![](https://i.imgur.com/hVrmVxa.png)
1. At the top of the **Blocks** section, click _Motion_ to view the Motion blocks
1. Find the "change x by {10}" block, and _snap_ it under the "when" block in the **Scripts** area  
    ![](https://i.imgur.com/Y3QWa5B.png)
1. On the "when" block, click the dropdown where it says "space" and change it to "right arrow"
1. On the **Stage**, see the sprite move to the right while pressing the right arrow key!

Create similar movement scripts for _left_, _up_, and _down_. Note that the "change x by..." block will move the sprite _horizontally_ (left and right), and the "change y by..." block will move the sprite _vertically_ (up and down).

## Smoother movements
Update the code so that it constantly checks if a keys are pressed instead of simply responding to keypresses:

1. Drag over the "when {green flag} clicked" block from the _Control_ section
    - This will cause the blocks beneath to execute when the user clicks the green flag
1. Under the "When" block, drag over the "forever" block from the _Control_ section
    - This will cause the blocks within to execute repeatedly forever
1. Within the "forever" block, drag the "if \<>" block
1. In the empty space next to the "if", drag a "key {space} pressed?" block from the _Sensing_ section
1. Within the "key pressed" block, click the dropdown where it says "space" and change it to "right arrow"
    - This will cause the blocks within the "if" to execute only **if** the right arrow key is pressed
1. Within the "if" block, drag the "change x by {10}" block from the _Motion_ section
1. Click the green flag, and see the sprite move on the **Stage** while pressing the right arrow key!

![](https://i.imgur.com/W8H8vIo.png)

>Note: If the sprite goes off the screen, right click it in the **Sprites** section and select "show"  
>![](https://i.imgur.com/XFL2qrG.png)

Update the movement scripts for _left_, _up_, and _down_ as well.