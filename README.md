# Create with Code Lab

## Unity Learn:  Junior Programmer Course

The goal of this lab is to complete a personal project using the basics, <small>and the new input system 🤫</small>, that are taught in the [Unity Learn Junior Programmer Course](https://learn.unity.com/pathway/junior-programmer).  Each week, starting with Thursday March 4<sup>th</sup>, 2021, I will attempt to hit the milestone listed.  A date of completion will be listed for each subtask as well as for each milestone.  A postmortem will be written after the completion of the course.

## Project Design Document

Project Began:  Mar. 4, 2021

### Project Concept

1 — Player Controls
: You control a Dog Knight in this 3D person dungeon crawler, where WASD & the mouse make the player move, look around, block, and attack.

2 — Basic Gameplay
: During the game, monsters appear from set spawn points when the level loads, and the goal of the game is to slay all of the monsters and rescue the dog knight's pet dragon Druug.

3 — Sound & Effects
: There will be sound effects when an actor attacks, block an attack, is damaged, or dies.  There will be particle effects when an enemy dies.

4 — Gameplay Mechanics
: As the game progresses, each room must be cleared of enemies so that the door to the next room will open.  There will also be a single physics puzzle to activate a switch to open a door.

5 — User Interface
: The enemy counter in the top right corner of the screen will decrease whenever an enemy is killed.  The health bars, located above each actor's head, will decrease when they are hit by an attack.  At the start fo the game, the title ***Doge Knight*** will appear, and the game will end either when Druug is rescued or the player dies.

6 — Other Features
: A restart option appears when the game ends.  The menu offers a choice difficulty that controls the heath and damage of the player and enemies.

### Project Timeline

Milestone 1 — Due 3/7 — Complete 3/7
: Initial setup of a testing grounds scene.

- [x] Packages imported
- [x] Assets imported
- ↑ Completed 3/4 ↑
- [x] Project settings
- ↑ Completed 3/6 ↑
- [x] Create basic level layout
- [x] Add player, monster, and Druug to the scene
- ↑ Completed 3/7 ↑

Milestone 2 — Due 3/14
: Setup player controls

- [ ] Setup New Input System
- [ ] Setup the move action
  - [ ] Walk animation
- [ ] Add a freelook rig to the player prefab
  - [ ] Add the component that make cinemachine work with the new input system
- [ ] Setup attack action
  - [ ] Attack animation
- [ ] Setup block action
  - [ ] Block animation

Milestone 3 — Due 3/21
: Setup basic gameplay

- [ ] Make the level slightly more complex
- [ ] Add monster spawn points
- [ ] Monsters move toward the player
  - [ ] Move animation
- [ ] Monsters can be damaged by the player
  - [ ] Damage animation
- [ ] Monsters can attack the player
  - [ ] Attack animation
- [ ] The player can be damaged by the monsters
  - [ ] Damage animation
- [ ] The player can end the game by touching Druug

Milestone 4 — Due 3/28
: Sound & Effects

- [ ] Sword attack SFX
- [ ] Monster attack SFX
- [ ] Shield block SFX
- [ ] Player damage SFX
- [ ] Monster damage SFX
- [ ] Player death SFX
- [ ] Monster death SFX
- [ ] Monsters explode into smoke after dieing

Milestone 5 — Due 4/4
: Gameplay Mechanics

- [ ] Create three distinct rooms
  - [ ] Basic room
  - [ ] Room with obstacles
  - [ ] Physics puzzle
    - [ ] Ball and a hole to roll it into
- [ ] Rooms open their doors when enemies are cleared
- [ ] Physics puzzle does physics puzzle stuff

Milestone 6 — Due 4/11
: Gameplay Mechanics

- [ ] Add enemy counter in the top right corner of the screen
  - [ ] Decreases whenever an enemy is killed
- [ ] Add health bars above each actor's head
  - [ ] Decrease when they are hit by an attack
- [ ] Add title screen
  - [ ] ***Doge Knight**
  - [ ] Start game button
  - [ ] Quit to desktop button
- [ ] Add game over screen
  - [ ] Restart button
  - [ ] Quit to main menu button
  - [ ] Quit to desktop button
- [ ] The game ends when the player loses all their health
- [ ] The game ends when Druug is rescued

Backlog — Due 4/25
: Additional enemies, running, jumping, and keys

- [ ] Add a second enemy
  - [ ] Spiny!
- [ ] Player can run by holding shift
- [ ] Player can jump by pressing space
- [ ] Add a mimic enemy
  - [ ] Attack animation
    - [ ] SFX
  - [ ] Surprise attack animation
    - [ ] SFX
  - [ ] Move animation
    - [ ] SFX
  - [ ] Damage animation
    - [ ] SFX
  - [ ] Death animation
    - [ ] SFX
    - [ ] Puff of smoke
- [ ] The mimic should drop a key to the room's door.
- [ ] Credits
