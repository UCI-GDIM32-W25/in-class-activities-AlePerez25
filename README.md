# GDIM32 In Class Activities


# Week1
### Activity 1

- Make notes.
- Don’t procrastinate!
- Read the pre-learning slides.
- Use out of class tools (YouTube / Unity documents).
- Take advantage of support when in need of assistance: peers, LAs, Office hours and discord.
-  Ask questions.
-  Learn how to use the inspector
-  Create map concepts. 

### Activity 2

- Q1: 10
- Q2: 2
- Q3: Print “hello world” in the console every frame
- Q4: MonoBehavior
- Q5: Print “x = 10” in the console when the program starts
 - Q6: The “(10)” is the argument assigned to show along with the text parameter “x = ” together that's why we need to use the “+” sign to display “x = 10”
- Q7: The _playerTransform variable is instantiated but never used.
- Q8: Transform.Translate should be replaced with _playerTransform.

### Activity 3

- link:

https://docs.google.com/document/d/1hYNliasaT5HCwedvTw8yrg4QrNS10bXhExGOnQw6uGg/edit?usp=sharing

# Week2
### Activity 1
![IMG_20260113_180422083](https://github.com/user-attachments/assets/d97cc72b-1e2c-4796-8156-67267484ddfc)

### Activity 2
- In today's class, I worked on my mini-game 2, creating the game objects, configuring the inspector for each of them, and writing a small portion of the code to make my penguin jump. This worked, but the problem is that if I continuously press the spacebar, my penguin flies because it performs a double jump. I need to fix that. I also created the other scripts, but I haven't worked on them yet.

# Week3
### Activity 0-2

- Partner name: Bella Sloan

### Activity 3

![IMG_20260120_191627832](https://github.com/user-attachments/assets/1b0e5515-0eb3-4eaa-9f14-ca51713aa626)


# Week4
### Activity 0
Bilal payton and Laura liu

### Activity 1

- Question 1: All the scripts of the locator objects disappear because the code indicates that they should be destroyed.

### Activity 2
![264714dd-43c7-4360-ab4d-a3f6d6017d73~1](https://github.com/user-attachments/assets/b81f6a20-4ffb-486c-8b87-478d1e714be9)

### Activity 3
[[MG4 Commit](963784650733fe8a03f64666623c3edc1497a2bb)](https://github.com/AlePerez25/HW4/commit/963784650733fe8a03f64666623c3edc1497a2bb)


# Week5

### Activity 1
- Personally, I think that's a good structure for using interfaces and abstract classes, but it needed many changes and there were small errors. However, I would change the organization.

### Activity 2
- From what I understand of this concept, the Model in this case is the player, who, upon approaching the enemies (View), sends a message to the Controller (game data), which then sends an input and displays the message. (I'm not sure I've understood the concept correctly.)
### Activity 3

- Scenario 1: 
    - Enums: To classify the different types of objects displayed on the screen.

- Scenario 2: 
    - Inheritance: To have a parent class and share the similar behaviors of each weapon, for example. 
    - ScriptablesObject: This is for enemies and the player themselves to see and establish, for example, how much health they have left.
    - Singleton + events: This can be useful for the UI and for the weapon sounds to subscribe to events.
    - Enums: For example, to show when other teams are eliminated, are winning, have low health, etc.

- Scenario 3:
    - State Mashings: For plants, to find out what things could affect plant growth.


### Activity 4

Attendance: Gianine Ariane, Kai Xaia Castillano and Alejandra Perez

Proposal: https://docs.google.com/document/d/1zNEI6Q6prvof6MZBIPg397B4LSM3YyidLB--5WPzAQw/edit?usp=sharing 

# Week6

### Activity 1

Demo notes: 

- Profiler:

    - Open in unity:
    Window —> analysis —> profiler

    - More important columns in hierarchy:
    1) Overview 
    2) Time ms 

    - The fruit prefab collider is a Polygeon collider but is not a good idea if it has a lot of small pieces of it a circle collider is better because is most smoothed and is not going to look lacking.

    - Keep the collider as simple as possible. 

- Performance and optimization:
 
    - Performance and optimization can help you to know how to run your game faster.
    Learn about performance and optomization!!

        - We can use Profiler in our final game if we have any problem with optimization 

- Gizmos:

    - Use circle collider gizmo.
    Gizmos.DrawWireSphere

    - With Gizmos you can track the player's right body  or other object movements.

    - Gizmos is only visible to the programmer.

        - For our final game we can use gizmos to track our NPC’s movement and player.

- BreakPoints:

    - Is a point in the code where the game is going to stop.

    - Help to see which piece of code is not going right.

    - Call Stack: Show the methods that you call

        - We can use this to debug our game and see which code is not working.

### Activity 2

Attendance: Gianine Ariane, Kai Xaia Castillano and Alejandra Perez

Final Proposal: https://docs.google.com/document/d/1zNEI6Q6prvof6MZBIPg397B4LSM3YyidLB--5WPzAQw/edit?usp=sharing 

# Week7

### Activity 1

Demo Notes:

- The red line on the duck represents the reaction distance if the chicken is within that range.

- However, if an object is obstructing that line, a circle will be displayed to indicate this.

- The duck has two movement modes: first, when it's about to attack the player, it moves directly into them; and second, every few seconds, it chooses a direction and moves in that direction.

- If the duck hits an obstacle, it leaves a yellow dot (Sphere Cast) and chooses another position to collide with.

- Ray Cast and/or Sphere Cast are ideal for helping the character see obstacles.

- The red line in the duck  is the visualisation of the raycast.

- Gizmos method draw the line with:
    - Gizmos.DrawRay

- OuthitInfo: 

    - The raycast method is going to fill in the information inside of the variable with the recast response.

    - Returns a true or false.

### Activity 2

Attendance: Gianine Ariane, Kai Xaia Castillano and Alejandra Perez

### Activity 3

<img width="1061" height="1260" alt="Screenshot 2026-02-17 180931" src="https://github.com/user-attachments/assets/2c2ba66a-2d8c-414e-af49-cd3dcf3ce4f3" />


### Activity 4

Trello link: https://trello.com/b/Xaon9XV2/gdim-32-group-board 

### Activity 5

https://github.com/Winterfall4/GDIM32-Final/commit/13e6168e44bb52679e080d272ef520419e6bd966 

We downloaded the animations for the main player. Now the player can move, and we also tested adding music.

# Week8

### Activity 1:
- Demo notes:

    - Bloom post-processing effect to look more professional and glow 
    - install package.
    - object + new layer + post_process Volume:
        - Bloom and color grading.
    - “Color filter” changes the aspect of the game.
    - look for filter in aunty asset store: 
        - Works with the rendering pipeline.

    - How to add one:
    - Import the effect, add it to the post processing object.
    - Change max intensity.

### Activity 2:

Attendance: Gianine Ariane, Kai Xaia Castillano and Alejandra Perez

### Activity 3:

- Playtest notes:
    - Lagging
    - Having hard time with camera
    - Sensitivity issues
    - Make a setting where players could change sensitivity
    - Rocks are launching people
    - People like the environment and UI

### Activity 4:

Trello link: https://trello.com/b/Xaon9XV2/gdim-32-group-board 
- I'm going to work on the flower garden and fix the rocks.

### Activity 5:

- I fix the rocks problem and I start the flower garden.

- Push link: https://github.com/Winterfall4/GDIM32-Final/commits/main/ 

# Week9

### Activity 1:

- Scaling: An architectural solution will scale well if, when the program is handling Lots of data..
    - its performant 
    - it’s easy for users - whether they’re other programmers or content makers - to add and make data.

- Be able to talk about how your solutions will be performant and easy for the user. 

- How scaling patterns relate to the programming design pattern?:
    - All of the design patterns we’ve learned will help you write code that scales well.
    - State machine, MVC, Abstraction and polymorphism.

- Create Scriptable objects to write dialogue this would make more easy to modify the dialogue.

- Canvas with replay bottoms to replay NPC’s

### Activity 2:

Attendance: Kai Xaia Castillano and Alejandra Perez

### Activity 3:

- Does the inventory systems feels natural? 
- Drop items with "Q" is a good iteam?

Playtesting notes:
- inventory system works well
- issues with camera still  move it to the left or right?
- maybe click e for grabbing items instead of mouse click?

### Activity 4:

- As a team, we feel we're halfway through the game, since most of what we need to work on right now is focused on NPC and main character dialogue. There are a few small details we need to work on outside of dialogue, but we consider them quick fixes.

### Activity 5:

- Push link: https://github.com/Winterfall4/GDIM32-Final/commits/main/
- I create another part of the environment and also import the dog asset to interact with it.

# Week10

### Activity 1:

- Attendance: Gianine Ariane, Kai Xaia Castillano and Alejandra Perez

### Activity 2:

- Playtesting notes:
    - camera still wonky 
    - Npc feature is cool
    - Alt mouse wonky 
    - Nice UI
    - Inventory bugs (full ui pops when it isn’t full) (objects not being able to be picked up even though inventory has space)

### Activity 3:

- Personally, as a team, we feel we are about 75% of the way to finishing the game. We are a little scared because the things that remain to be done are the most important and we are nervous :V.

### Activity 4:

- We asked LA for help creating a Navmesh to contain NPCs in a specific area and works!

- https://github.com/UCI-GDIM32-W25/in-class-activities-AlePerez25/commits/main/



























