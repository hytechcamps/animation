# Snap
Use [Snap](https://snap.berkeley.edu/snapsource/snap.html) to create games and other programs!

## Playing an existing game
Open the [existing game](https://snap.berkeley.edu/snapsource/dev/snap.html#present:Username=josephmaxwell&ProjectName=building%20blocks) and play around with it. Try to win the game by reaching the LIFE bar!

## Replacing the sprites
Replace the existing game sprites with the newly created sprites from Piskel. From the existing game, click the "minimize" button to show the code.

![](https://i.imgur.com/2QQupy8.png)

Then, follow the instructions below!

### Power up
1. Export the power up sprite from Piskel
1. In the **Sprites** section, click on the _Star1_ sprite to select it
1. In the **Scripts** section, click on the _Costumes_ tab
1. In Windows File Explorer, locate the image file for the new power up sprite (exported from Piskel)
1. Drag the image file into the _Costumes_ section
1. See the star update on the **Stage**!

Repeat the steps above for the second power up was well.

### Enemy
1. Export the enemy sprite (both frames!) from Piskel
1. In the **Sprites** section, click on the _Enemy_ sprite to select it
1. In the **Scripts** section, click on the _Costumes_ tab
1. In Windows File Explorer, locate both of the image files for the new enemy sprite (exported from Piskel)
1. Drag both image files into the _Costumes_ section
1. Delete the old costumes
1. See the enemy update on the **Stage** after clicking the green flag!

Repeat the steps above for the second enemy up was well.

### Player
1. Export the walk cycle player sprite (all frames, including the standing frame) from Piskel
1. In the **Sprites** section, click on the _Player_ sprite to select it
1. In the **Scripts** section, click on the _Costumes_ tab
1. In Windows File Explorer, locate all of the image files for the new player sprite (exported from Piskel)
1. Drag all image files into the _Costumes_ section
1. Delete the old costumes
1. Make sure the remaining costumes are in the proper order
    - Drag and drop within the _Costumes_ section to reorder if necessary
1. Right click on the standing frame, and select "rename"  
    ![](https://i.imgur.com/Z68ryNm.png)
1. Rename the standing costume to "stand"
1. See the player update on the **Stage** after clicking the green flag!

## Challenges
Complete the following challenges in Piskel and Snap!

### 1: Background
Create a background for the existing game. Select the _Stage_ from the **Sprites** section, then click on the _Background_ tab. Either edit the existing stage background, or import a new one!

### 2: Change the speed the player moves
Find the place in the code that determines how much the player moves each cycle. Then, update it so the player moves a greater distance each time!

>Hint: look for the ![](https://i.imgur.com/ENHuu9J.png) block in the existing Player sprite scripts! 

### 3: Change the speed of the enemy animation
Find the place in the code that determines how quickly the enemy sprite moves from one frame to the next. Then, update it so the enemy animates with a faster frame rate!

>Hint: look for the ![](https://i.imgur.com/NaMnlgU.png) block in the existing Enemy sprite scripts!

### 4: Duplicate an existing enemy and place another enemy in the game
In the **Sprites** section, right click on an existing Enemy sprite and select "duplicate" to create a new one. Place the new enemy somewhere on the stage!

### 5: Life count
Start the player with four lives instead of three

1. In the **Sprites** section, select the "health Bar" sprite
1. In the **Scripts** section, find the block where `life count` is set, and change it to from `3` to `4`
1. On the _Costumes_ tab, create a new costume for a health bar with 4 lives
1. On the _Scripts_ tab, update the code so that if `life count` is 4, the proper costume appears for the health bar

### 6: Decoy star
Update the first power up sprite so that it _decreases_ the jump height of the Player instead of increasing it!

1. In the **Sprites** section, select the "Star1" sprite
1. Find the block where the `jump-vel` is set, and change the value!

### 7: Power up animation
Add an animation to the power ups! Go back into Piskel, and add a new frame to the power up sprite. Then, import both frames into Snap, and copy the Enemy scripts so that the frames switch constantly!

### 8: 