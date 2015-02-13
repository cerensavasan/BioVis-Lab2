# BioVis-Lab3
## Repository of Simulation
[GitHub](https://github.com/cerensavasan/BioVis-Assignment1.git)

## Currently Supported Interactions
### The user can pause the grid.
   This interaction is mostly allows for examining the grid closely without it changing. It helps the user understand where each cluster is and they can also learn to anticipate certain clusters to stabilize and others to grow out of control.
   
### The user can create a cell by clicking on an empty space on the grid.
  
  Being able to manipulate the board is an important power to give to the user because the user can determine the entire course of the simulation by merely adding one cell that will make a stabilized cluster grow exponentially. It will also help the user understand some of the life/death rules, say, if they decide to create an isolated cell and see it die.
  
### The user can kill a cell by clicking on it.
  
  This allows for the user to manually stabilize clusters and create a habitat that will last and stabilize.
  
### The user can clear the grid completely.
 
  Killing all cells allows the user to start over by manually creating clusters as opposed to the randomized initialization. This is more effective if the user pauses before creating any new cells.
  
### The user can reset the board and get a new random set of initial cells.
 
  Revisiting the simulation several times helps greatly with understanding patterns and figuring out the logic behind what makes cells die, get born or survive. 
  
## Suggested Improvements to Interaction
### Key/Mouse Guide
There should be a visible table on the visualization that has the key/mouse instructions on how to interact with the grid.
As the person who created the visualization, I know every part of it. A user who has never seen it before can not anticipate any interaction without proper documentation and guidance. The biggest change I would make is to inform the user on how to interact with the grid by giving them that information. I would even suggest the creation of a main page where one can first read about what the visualization is depicting and a guide on how to use the functionality effectively. The guide would cover the basics like what each key or mouse button does and explain how they can be used together. An example is to clear the grid and then create a few clusters while paused to see the outcome. I came across this problem when I showed a friend proudly what I had accomplished and they had no understanding of what they were even looking at and did not know it was interactive.
### Time/Cell Count Graph
A great way to help the user track the changes that are on the grid. It conveys a lot of information, such as the elapsed time, the amount of cells on the grid and eventually, the realization that the cell population growth is exponential. It could be useful to add a button that either reveals or hides the graph based on the user's needs.
### Color Change
Taking a second fresh look at my simulation made me realize that the black and white combination makes it very hard to see the whole grid in a meaningful way because it deceives the eye. Surely there is a better pair of colors that would not create an eye illusion and fit more with the color scheme of the program. The only concern is to exclude color pairs that may appear the same for the color blind. Orange and blue would be my pick.
### Grid Size
Giving the user the option to choose the size of the grid could be a great addition, as it allows them to adjust the scale of the experiment. This could be done by using a slider with several size settings to choose from, or by prompting the user to choose one of several buttons with predetermined grid sizes before the simulation starts and adjusting accordingly.
### Randomization Settings
If the user was allowed to pick the frequency of cells that are generated at initialization, it could affect the outcome of the experiment and the learning process of the user. The ability to experiment with different population sizes could also create a data set that the user is looking to observe.

## Prototypes

### Beginning phase of the simulation:
![Beginning phase of simulation](http://i.imgur.com/Fqrxsm9.png)

### A later phase of the simulation:
![A later phase of simulation](http://i.imgur.com/PUhdVFg.png)
