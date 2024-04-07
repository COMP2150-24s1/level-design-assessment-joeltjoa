[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Joel Tjoa
### Student number: 47240563 

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)

## 1. Player Experience 

### 1.1. Discovery
The element of discovery is essential in my level design as each section builds on the skills that were found in the last to create flow. As the player learns the core mechanics, the level is designed to at the same time test the boundaries of these same mechanics. For example at the start of section 3 the player has to make a long jump over some spikes that are 4 squares high. This immediately teaches the player two things; that the maximum jump height is 5 squares and that the platform is too far away to reach without the use of other skills. This forces the player to start experimenting and eventually discover that the staff attack comes with a dash of movement that they can use to gain more movement while in the air which is hinted at through the staff pickup at the start of the section. This is good design practice as it gives the player a sense of autonomy and rewards them for discovering a solution.
IMAGE

### 1.2. Drama
The intensity curve of the entire level sees a gradual incline to start as the mechanics are introduced then an increasingly sharp upwards curve in the following sections with a release of tension at each checkpoint and at the end of each section. The first design choice that facilitates a modulating intensity was to place checkpoints after the most intense encounters of each section to give the player a sense of reward for completing the challenge and allow them to not repeat the section of the level they just overcame. The density of enemies and obstacles in an encounter is the primary indicator of the intensity as it can evoke an emotional adrenaline response and creates memorable moments of tension. One example of this is in section 2 in which the encounter includes a spitter, destructible walls, spikes, acid and moving platforms which all happen simultaneously to add to the intensity. The tension from this section is built from both challenge and also its length between checkpoints that increases the risk of having to repeat more of the section the further they progress, which is then relieved once they reach a checkpoint.

### 1.3. Challenge
The main challenges in my level are physical that involve the player’s reaction speed, jump height and movement precision, and combos. I have controlled the difficulty curve of the level through building upon the skills and combos learnt in the previous section so that the player is familiar but challenged with the new encounters to keep interest and flow. Balancing is done through the use of health pickups and checkpoints as agents of intensity relief, and all of the encounters were playtested by myself to be sure they were possible with an optimal amount of challenge. One example of this can be seen in the third section of the game. At the start of the encounter the player must wait for the moving platform obstacle to move away, jump over some spikes then dash using the staff weapon to make enough distance to land on the first platform, avoid the spitter’s spit, crouch under the platform as it moves over them, then repeat the process to reach the end of the encounter. This creates a physical challenge for the player to time each action perfectly to achieve success and create flow as a result.

### 1.4. Exploration
My game facilitates a sense of autonomy by having the start and end point of the level originate in the same room with passthrough platforms which creates a centric layout that each section branches from. This means that the player quickly learns that without all three keys, the door will not open and they cannot complete the level and encourages them to start exploring in a direction that they choose to try and find them. A memorable space that I created is located at the end of the first section where there is a crossroads with one path blocked by a box and a small 2x2 pit of acid. This layout forces the player to move upwards where they can see another pushable box that would be able to fill the acid pit that they can only move away from the pit from this side of the box. This encourages the player to continue upward towards the obstacles of which they can then see a second key. Alternatively, if the player decides to wander past the second key to the edge of the platform, they will be able to see the final key which then in turn encourages them to find a path to the next section.


## 2. Core Gameplay 

IMAGE
### 2.1. Passthrough Platform
I chose to introduce the passthrough platform as the first mechanic because of its simplicity and its necessity to the centrality of the level.

### 2.2. Weapon Pickup (Gun)
The gun was chosen to be introduced next to adhere to the intensity curve due to the lack of external pressures at the start of the level allowing them time and autonomy to figure out the mechanic at their own speed.

### 2.3. Spikes
I chose to introduce the spikes at this stage because it introduces the player to the jump and health mechanics as well.

### 2.4. Chompers
The Chomper was added as an enemy using context clues from the previously introduced weapon and placed across a gap so it could not attack the player with its melee ability so as to ease the player into the level and add to the flow and intensity curve.

### 2.5. Health Pickup 
The Health Pickup was added after the first couple of obstacles as a moment of relief for the player and to also teach the player that the health losses are not permanent.


IMAGE
### 2.6. Acid
In this next encounter the acid was introduced as a step up in intensity from the spikes as they force the player to die and respawn and are also more efficient in creating negative space than the spikes.

### 2.7. Moving Platforms
Now that the player has gotten the basics of the movement mechanics, the moving platforms were added to create an increase in the intensity curve.

### 2.8. Checkpoints
The first checkpoint was chosen to be added at this point to give a sense of relief as the player has made a decent amount of progress across the first section. The checkpoint was added over acid to let the player discover the mechanic of changing their spawn point assuming the player falls into the acid.

IMAGE
### 2.9. Weapon Pickup (Staff)
I chose to introduce the staff here so that the player learns about both the abilities of the staff and the limitations of the previously attained gun not being able to shoot through or destroy the destructible wall. 

### 2.10. Destructible Wall
The destructible wall was introduced at this stage to provide a small increase in challenge and intensity to the player to prevent the player from advancing further without experimenting with the staff weapon and also provide protection to the spitter behind it.

### 2.11. Spitters
I chose to introduce the spitter here because it is protected behind the wall and is able to teach the player about its spitting mechanic.

IMAGE
### 2.12. Pushable Box
Towards the end of the section I chose to introduce the pushable box as a simple mechanic that adds to the player’s autonomy and exploration.

### 2.13. Keys
As the final new mechanic of the introductory section, the key being placed at this point gives context clues to the player that keys will be found at the end of each section.


## 3. Spatiotemporal Design
 
### 3.1. Molecule Diagram

### 3.2. Level Map – Section 1

### 3.3.	Level Map – Section 2

### 3.4.	Level Map – Section 3

## 4. Iterative Design (~400 words)
Iterative design was integral to the improvement of my level design as I did not start the process with a pre-planned spatial map of the level, therefore I had to use iterative design with trial and error to create the final product. The first image shows the level as it started out with the room with a door and three keys. As my level continues to evolve I decided to keep the first room while removing the keys and adding a passthrough floor to keep this room as a central place to the level and continue extending underneath the room.



After designing the first iteration of section one I decided to extend the platform underneath the tower encounter to emphasise the introduction of the staff weapon’s mechanics and balance the challenge from the moving platforms by moving the spitter’s range away from the player as they are jumping from that encounter. Additionally I decided to use the pushable box as another optional prefab to create further potential for interconnectivity in the later sections.



As I playtested the first iteration of section 2, I noticed that the challenge faced in the overpass encounter was too great for the intended curve at that point so in its second iteration I extended the gaps between the walls and spikes to give the player more time to react and also provided them with 2 additional health pickups as some intensity relief.




The third section went through many iterations as I tried to create an encounter that would act as the climax of the level from both a dramatic and challenge standpoint. This constant iterating came from my own discovery of the limits of the mechanics and how far I would be able to push the player in this encounter. Through this iterative design process I decided that the player would need many reliefs through checkpoints and health pickups, but challenged the player to complete 3 out of 4 levels of the section before they earned a checkpoint. Through my iterative design process I also developed a new way to utilise the moving platform as an obstacle rather than a tool for the player which added to the subversion and challenge of the encounter.

Although all parts of my level underwent the process of iterative design, I believe that section 2 would still benefit from further development under the same process as the lack of longevity of the encounter is a weak point.

## Generative AI Use Acknowledgement
