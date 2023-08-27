# TRILOGY
A complete game with sound- and animation effects written in assembly (MASD syntax) on and for the HP49 calculator / saturn processor.

(The source is in [TYII.A](https://github.com/M64GitHub/TRILOGY-HP49/blob/main/TYII.A), which is the only file required. Images within the repository are used for illustating this readme)

### Installation
You can assemble the game by activating the builtin development library:
```
256 ATTACH
```
Then put `TYII.A` on the stack and press 
```
→PRG
```
to build. It will replace itself with the binary you can play. Store that object like any other stack item. Retrieve like any other object to play.

### The Game
This is a logic game, consisting of many levels. Levels can be bigger than the actual screen. The levels consist of a field with different types of stones placed onto it:

 - regular stones showing a symbol
 - moving stones showing an arrow
 - wall stones
 - rotation stones: make the moving stones change their direction

There are regular stones, and special stones that can move. **Moving** stones will stop on any other stone (or the border) in their way. They show their moving direction as an arrow.  

**Rotation** stones will defer the way a moving stone moves. When a moving stone hits a rotation stone, it's direction changes.

Often, moving stones are blocked by regular stones on start. Once you make regular stones disappear, they (the moving stones) start moving and can complicate / change the logic you had in your mind ;)

### The Rules
Select any 3 same stones located in the shape of a **rectangular triangle** to make them disappear (like in the shape of the L within the logo you can see below).  

When all regular AND moving stones have disappeared, the level is solved.  

Only wall stones and rotation stones can be left.

### The Points

 - every dissolved triangle gives 5 points
 - every completed level gives 100 points
 - a bonus points countdown starts from 100 points and decreases every few seconds
 - the faster you complete the level, the more points

### Animations showing the game

Start Screen, Level 1-2  
![](https://github.com/M64GitHub/TRILOGY/blob/main/t1.gif "")  

---
Level 3  
![t2](https://github.com/M64GitHub/TRILOGY-HP49/assets/84202356/a392974f-daef-49c3-987d-397fcea01787)

---
Level 4-6  
![t4](https://github.com/M64GitHub/TRILOGY-HP49/assets/84202356/5945a1fa-7cdb-497a-b856-a6f02051f5c8)

---
Level 7-8  
![t4](https://github.com/M64GitHub/TRILOGY-HP49/assets/84202356/2531b0dc-a14c-4fd7-ba51-2eaa5d92396b)
