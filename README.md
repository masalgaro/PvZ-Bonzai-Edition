# Plants vs. Zombies: Bonzai Edition

A demake of the popular and beloved tower defense game made entirely in the Jack high level language featured in the [nand2tetris online course](https://www.nand2tetris.org/).  
While this version of the game is a lot more limited due to working within the limitations of the Hack computer, it still features a solid recreation of the strategic gameplay you've come to expect from the source material. Plant plants, and get rid of zombies on the lawn.  

## How to execute this project

The official nand2tetris website links to an online IDE that features a *Jack compiler*. By cloning/downloading the repository and uploading the `.jack` files to the compiler, you can compile the files and play the game in its entirety using the *VM Emulator* provided in the website.  

### Controls

* **Arrow keys:** Move the *cursor* to select where to plant.  
* **S:** Plant a *sunflower*.
* **P:** Plant a *peashooter*.  
* **W:** Plant a *wallnut*.  
* **C:** Plant a *cherrybomb*.  

Sun is automatically added to your counter as sunflowers produce it, so there's no need to hover over them periodically.  
Keep track of both sun costs and plant cooldowns, and try to survive until the timer runs out!  
You lose the game if a zombie breaches through your defenses and exits reaches the left side of the screen, no lawnmowers to save you in this one.  
