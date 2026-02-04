# GDIM32 In Class Activities
## Instructions
Put each week's activities under new headers like the one shown above. Headers are created with the # symbol. More # symbols = smaller header.


Hit enter TWICE to create a new line.

# Week 1: In class activities

## Activity 1
1. Don't procrastinate on weekly minigame assignments and submit it on time. 
2. Make sure you have enough storage on your computer.
3. Ask the professor for help during office hours or the TA's for extra help.

## Activity 2

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
 
[Proposal](https://docs.google.com/document/d/1Ax2Mq7j3RwbZEpmFtbBaP7coQjp67ePpT8dRNFPnmxk/edit?tab=t.0#heading=h.y4j3q551ojs1)

- Create bullet points by writing dashes.
- Here's another bullet point entry.


Remove all placeholder text in order to get full credit for README file formatting.
