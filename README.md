# Mario Dino Game
## This project makes a web extension play the Mario Dino Game.
#### Created by Dhruv Sharma
##### Last Edited on May 16th, 2021

## Instructions to Run the Project:

**Method 1:**

  1. Download and unzip the project. Then, type in chrome://extensions/ in your url tab.
  ![Step1](images/instructions/Step1.png?raw=true "Step1")

  2. Click on the "Load unpacked" button and select the unzipped folder.
  ![Step2](images/instructions/Step2.png?raw=true "Step2")

  3. The extension should appear in your extension bar on the top right. Click on the Dino Icon on the extension and enjoy the game!
  ![Step3](images/instructions/Step3.png?raw=true "Step3")


## File Descriptions:

  * neterrorMario.html - This is the html file that runs when the extension icon is clicked on.

  * README.md - This file: the file that directs the user on how to use this project.

  * about.html - This page displays information about the creaters of this project, the script, and the Raspberry Pi version of this project.

  * app.js - This file allows the html button logic to be implemented in the story. It allows certain pages to be accessed depending on the choices of the user. I may use this in the future to add a connection to a database to keep track of users' save checkpoints.

  * manifest.json- This file specifies various details about the extension including the main html file, the ectension icon, etc.

  * popup.html, popup.js - Would have been my title page for the extension (to do in the future).

  * background.js, options.js, and options.html - Test files I made using the Google extension tutorial (changes the page background on tutorial website)

**'images' folder:**
  * I currently have many photos stored in this folder that I use as sprites, icons, or for the instructions The pictures that I am using in my project are the following:

  * 1xMarioSprite.png and 2xMarioSprite.png are the sprites for Regular Mario in the extension.

  * 2xOldMarioSprite.png is my old Tall Mario sprite that I replaced with the aforementioned sprites.

  * 1xDinoSprite copy.png and 2xDinoSprite copy.png include all the sprites for the game (had Dino instead of Mario).

  * DinoSprite.png is the sprite for just the Dino.

  * dino.png, dino16.png, dino32.png, dino48.png, and dino128.png depict the icon of the extension.

**'audio' folder:**
  * includes various cound effects that I plan to integrate in the Mario version of the Dino Game.
  
  Within the images folder there is an 'instructions' folder. There I have images of Steps 1-3 of installing and running the extension.
