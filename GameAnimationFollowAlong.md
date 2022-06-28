# Game Animation
Artists often create pixel art animations to be used in retro-style games. Follow the instructions to modify an existing game with new custom art! Google Chrome is recommended for this activity.

## The Existing Game
For the purposes of this exercise, there is an existing game within a Repl project to use. Start by creating a fork of the game, and playing it.

### Hyland Student credentials:
- Username: **hylandstudent**
- Password: **Learn2Code!**

### Instructions
1. Go to the [Existing Game Repl Project](https://replit.com/@HylandOutreach/Platformer)
1. Click the "Fork" button in the upper right
1. Log into Replit using the credentials above
   - _Note: It may be necessary to click the "Fork" button again_
1. Click the "Run" button to run the game
1. Expand the Preview area so there is room to play the game

![](https://i.imgur.com/2u6mfas.png)

Play through the game to see how it works!

## Modifying the Player Walk Cycle
Next, create your own version of the player walk cycle. At this point, try not to change too much - it will always be possible to come back and further customize the player.

### Importing the Existing Player
Follow the steps below to import the player sprite.

<img src="player.png" style="border: 1px solid black" width="300px">

1. Right click the picture above and select "Save image as..."
1. Save the image on your computer with **player.png** as the name
1. Open a new web browser tab, and go to [www.piskelapp.com](https://www.piskelapp.com)
1. Click the "Create Sprite" button  
    ![](https://i.imgur.com/EPj1iRr.png)
1. In the sprite editor, on the right, click the "IMPORT" folder icon  
    ![](https://i.imgur.com/RLRo3iQ.png)
1. In the menu that appears, click the "Browse images" button  
    ![](https://i.imgur.com/q5hAfOl.png)
1. Find the saved **player.png** file and select it for opening
1. Select the "Import as spritesheet" option  
    ![](https://i.imgur.com/wTxaoB7.png)
1. Set the Frame size to 32 x 32
1. Click the "import" button  
    ![](https://i.imgur.com/Ajb8yRD.png)
1. If a pop-up appears asking if you want to continue, click the "OK" button

Now the four frames of the player sprite should be ready for editing!

### Modifying the Player
Now, the next step is to update the player sprite a little bit.

1. Make a small change to the player, like the color of their head
   - Do not change the number of frames
   - Do not change the size of the canvas
   - Do not change the basic "Walk Cycle" frames
   - Make sure to change each frame of the animation 
1. Click the "Export" button on the right side of the window  
   ![](https://i.imgur.com/8pW6Lrg.png)
1. Make sure "Scale" is set to **1.0x**
1. In the EXPORT menu, select the "PNG" tab  
   ![](https://i.imgur.com/B7T4DY9.png)
1. Change the "Spritesheet layout options" so there are **4 columns**  
   ![](https://i.imgur.com/zIgoynp.png)
1. In the "Spritesheet file export" part, click the "Download" button  
   ![](https://i.imgur.com/1KhYoV5.png)
1.  Save the file somewhere with the name **player.png**

Now the updated player should be ready to enter the existing game!

## Putting the New Player in the Game
It's time to update the game itself with the new player.

1. Go back to the Repl project tab
1. On the left, open the "Files" menu  
   ![](https://i.imgur.com/EPqBgcN.png)
1. In the "Files" area, open the "images" folder  
   ![](https://i.imgur.com/lLOjCWp.png)
1. Drag the **player.png** file into the "images" folder  
   ![](https://i.imgur.com/tOOkHNe.png)
1. In the popup that appears, click the "Replace" button
   - This will overwrite the existing **player.png** file

Run the program again, and at this point, the new player should appear!

## Next Steps
After the follow-along activity, there are some [challenges](AnimationChallenges.md) to complete. Or, you can feel free to get creative and do whatever you want to do with Piskel!