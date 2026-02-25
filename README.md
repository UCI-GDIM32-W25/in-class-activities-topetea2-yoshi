# GDIM32 In Class Activities
## Instructions
Put each week's activities under new headers like the one shown above. Headers are created with the # symbol. More # symbols = smaller header.


Hit enter TWICE to create a new line.

# Week 1: In class activities

## Activity 1
1. Don't procrastinate on weekly minigame assignments and submit it on time. 
2. Make sure you have enough storage on your computer.
3. Ask the professor for help during office hours or the TA's for extra help.

## Activity 2:

Q1. 10 is the value


Q2. Since the code is a repeated loop, the value will be 2.


Q3. Prints out hello world once you run the code. 


Q4. MonoBehavior 


Q5. X = 10 is going to print at the start of the game


Q6. int = 10 is our parameter and "x = " + X is a Debug.log method that will be printed out on the console.  


Q7. The code is using a datatype value, which will not compile once we run the game. 


Q8. We change Transform to _playerTransform in order to fix the error. 

## Activity 3
[Google doc](https://docs.google.com/document/d/1A1lkqSfYbcQn9UN1hMjbRY7x2fuXZEa0aiapVb3bzUQ/edit?tab=t.0#heading=h.7bwi6hg1wejp)


# Week 2:  In class activities

## Activity 1: 
![Image](https://github.com/user-attachments/assets/206f0fec-e795-4420-b785-840056ba326e)


## Activity 2:

[Commit](https://github.com/UCI-GDIM32-W25/mg2-topetea2-yoshi/commits/main/)

2. One thing that I was working on was the layout of the game by adding the platform, coins, and player. I've also started some coding in the process and added some colliders to the GameObjects.

# Week 3:

## Activity 0-2 

Partner: Ruth Sun


## Activity 3

[Image](https://github.com/user-attachments/assets/17e7f7d4-07dc-486a-a0d8-7880205ae13f)



# Week 4:

## Activity 0:

Partner: Ruth Sun


## Activity 1: 

When mutiple locators are set in the scene, most of the gameobjects loses its script once the game runs. In our code we wrote "Locator.Awake()," which deletes the extra "Locator" scripts from some of the components, leaving only one script in the scene.


## Activity 2:

<img width="4080" height="2296" alt="image" src="https://github.com/user-attachments/assets/77eed324-90ba-4461-847a-e0c6080969e0" />

## Activity 3: 

[Commit](https://github.com/topetea2-yoshi/HW4/commit/d3ea75ab614152b49b0cbf1d8c96a0231f2b2ee3) 

For MG4, I imported the assets in the unity project and slice every single sprite individually. 



# Week 5:


## Activity 1:

After fully looking at the code, the separation between the abstract Item class and the IBreakable interface is pretty straightforward. But personally, I don't think that breakability needs to be a seperate interface. Only two items in the systems are breakable, and both of them already share the same type of durability logic. Because of that, I feel like breakablilty could just be handled inside a child class of item, instead of them being two seprarate interfaces. 

The current intefaces aren't wrong, but if I were to build a large project, I'd probably group breakable items into the same class, instead of using an interface. 


## Activity 2:

## The Model:

W1:
 - EnemyW5Demo1
 - ItemW5Demo1


W2: 
- EnemyStats Script
- ItemW5Demo2 Script 

## The View: 


W1: Barely has UI Script


W2:
- Inventory UI Script 

## The Controller: 
 D1:
 - PlayerW5Demo1
 - EnemyW5Demo1
 
 D2:
 - PlayerW5Demo2 Script
 - EnemyW5Demo2 Script
 - Dialog Script (handles with input and game logic)

## Activity 3: 
## Rythum Scenario 


ScriptableObject:
  - Store hundreds of beats cleanly without cluttering the scene.
  - Edit beat timing and patterns without touching code.
  - Organizing beatmaps per song
 
  
Basic parent class + polymorphism:
 - Beats share core fields (key, time, position)
 - A parent beat class that shares logic in one place
 - Have special beat types to override behavior


Singleton:
 - Timing source to stay in synced with the music
 - Prevents timing conflicts or mutiple music managers running at once.
 - Controlls song time, beat spawning, hit windows, and sync between visuals and audio. 


## Team Shooter Scenario:

Basic Parent Class + Polymorphism:
 - characters share core systems (health, movement, animations)
 - Base class to prevent repeatition of the same code to every player
 - Characters override unique abilities like special attacks, Ultimate abilities, and movement abilities to not interfere with the structure.


Abstract + Inferfaces: 
 - Character have different type of abilities like damage and movement
 - Keeps the character class intact from becoming bloated with other pieces of code.
 - Creating interfaces or abstract Ability classes let each ability define its own behavior.


ScriptableObject:
 - Store character stats, ability data, cooldowns, and damage values
 - keeping data away from interfering with scene objects.
 - Balancing characters

Finite Machine:
 - Characters constantly switch between states (Idle, running, shooting, reloading)
 - Sync gameplay logic with animations.
 - Keeing translations cleaner and predictable.



## Farming Scenario:

ScriptableObject:
 - a way to store the character and plant assets.
 - durability
 - How long it takes for a plant to grow.
 - how much an item sells from every plant you harvest. 

Inheritance with polymorphism: 
 - Player class to add movement for character GameObject
 - Plant class where the player has the ability to place crops at any area.
 - Harvest class: Making the player break items to gather up resources.
 - Add potential interfaces like IPlantable, Iharvestable, or Ibreakable
 

Finite machine with enums: determines how the player will interact with the plant and resources. 
- idle, walk, run animations
- Crops could naturally moved through states. (Seed > Grow > Harvest)
- Ensures visuals and gameplay stay in sync as crops grow.


Model-View-Controller: 
- How many plants are being calclated 
- Helps organize the farming logic cleanly.
- keeps systems decoupled (crops could notify the UI without hard‑coded references.).


## Activity 4: 

 In attendance: Ruth Sun, Armando Topete, and Micheal A. Lopez


 # Week 6:

 
 ## Activity 1:

 Profiler:
 
 Having a problem with performance? 
  
   - The profiler could help - Window > Anaysis > Profiler

   - The Profiler can show how long each frame takes and which methods are slowing the game down?

   - Debug.log spam and allocating variables inside loops can tank performance.

   - For my final project, I could potentially use the Profiler to check if my movement or UI scripts are causing frame drops

 
 


Gizmos:

- Gizmos are useful to resolve vectors?

- Gizmos can visualize things that don't normally show up in the Scene view, like range, spawn points, or detection areas.

- I can use gizmos in my final project to debug player interaction zones or enemy patrol paths.


Breakpoints: 

- Breakpoints let me freeze the game at a specific line and inspect variable values.

- This could be useful for debugging a characters movement or item interactions in my final project.



Merging: 
- Git conflicts happen when two people edit the same part of a file.

- For my final project, we should avoid editing the same scene at the same time.




Performance: 
 - Using simple colliders could improves physics performance.

- For my final porject, i'll avoid using mesh colliders and maybe keep physics simple.

  
Extra comments: 

- We tend to lose points if you don't have a proper itch build?

 ## Activity 2

 In attendance: Ruth Sun, Armando Topete, and Micheal A. Lopez

 [Proposal](https://docs.google.com/document/d/1Ax2Mq7j3RwbZEpmFtbBaP7coQjp67ePpT8dRNFPnmxk/edit?tab=t.0#heading=h.y4j3q551ojs1)





 # Week 7:


 ## Activity 1:

   - Raycasting is important for navigation???
   
  
   - hitInfo.point???


   - The sphere attacted with the duck is Visualizing a sphere cast?

   -  The _state variable is used to store the duck’s current state and decide which
state function (RunWanderState() or RunPursueState()) to run

 -  using a raycast for line of sight


 
 ## Activity 2: 

 
  In attendance: Ruth Sun, Armando Topete, and Micheal A. Lopez


 
  ## Activity 3: 
   
  [Final Breakdown](https://docs.google.com/drawings/d/1TlOGyu_tVXlUOBFmQ2MWB6SKHNz_H9fCyD2_SFWiyGc/edit)
  
  
  ## Activity 4: 
  
  Ruth: Hand/gamecontroller, the player class, item class, 
  
  
  
  Armando: UI, SFX, Item design, 
  
  
  
  Micheal: World building, terrian, apple tree,  



  ## Activity 5: 


  [Commit](https://github.com/rsun050/handy-dandy/commit/b275e04e672cb743551bd79d92b518c8ccd1af8a)

  
  
  Some things that I've been working on is the UI and the character designs, which are still in early development. 
  
  
# Week 8

 ## Activity 1

Notes: 



Pro processing:

- Adds a visual “filter layer” on top of the camera.
- Doesn’t change gameplay — only the look and mood of the scene.
- Small tweaks = huge difference in atmosphere.




Global Volume Setup

 - Create a Global Volume → assign a Profile.
 - All effects live inside that profile.
 - Toggling effects on/off helps compare changes quickly.



Bloom

- Makes bright areas glow.
- Good for lights, pickups, UI highlights.



Package system????
  
  
  
  
  
 ## Activity 2: 

 
In attendance: Ruth Sun, Armando Topete, and Micheal A. Lopez




## Activity 3: 
Captian: Michael 

Comments on our game: 
Make the mouse sensitivity start out lower, and give the player to open a Settings menu where they can adjust their mouse sensitivity accordingly. Add more to do in the game, like a lake and cave in the back of the village. Add some more environmental props like bushes or wild-life. Fix the bug where looking at an object for the first time makes your mouse freak out. 



## Activity 4: 

 - Micheal: All of the Game Design parts
 - Ruth: working on the programming
 - Armando: Physical hands design, Inventory UI, Quest UI, Animation, NPC dialog, 2D art for NPC characters.



## Activity 5:

[Commit](https://github.com/rsun050/handy-dandy/commit/729cf2ffe54b90820bf5fa76cafdbd518d4b8b72)

I was working on the Inventory UI and the code is in early development. 



  
- Create bullet points by writing dashes.
- Here's another bullet point entry.


Remove all placeholder text in order to get full credit for README file formatting.
