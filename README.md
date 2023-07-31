# TRILOGY
A complete game with sound- and animation effects written in assembly on and for the HP49 calculator / saturn processor (5bit processor!)

(The source is in [TYII.A](https://github.com/M64GitHub/TRILOGY-HP49/blob/main/TYII.A), which is the only file required. Images within the repository are used for illustating this readme)

### Installation
Put TYII.A on the stack and press enter to assemble. It will replace itself with the binary you can play.

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

![](https://github.com/M64GitHub/TRILOGY/blob/main/t2.gif "")  
---
Level 4-6  

![](https://github.com/M64GitHub/TRILOGY/blob/main/t3.gif "")  
---
Level 7-8  

![](https://github.com/M64GitHub/TRILOGY/blob/main/t4.gif "")  


Start Screen with scroller
![Start Screen with scroller](https://github.com/M64GitHub/TRILOGY/blob/main/1.png "Start screen with scroller")  
---

Example Screenshot of a Level
![Example Screenshot of a Level](https://github.com/M64GitHub/TRILOGY/blob/main/2.png "Example Screenshot of a Level")  
---


Example Screenshot of a Level
![Example Screenshot of a Level](https://github.com/M64GitHub/TRILOGY/blob/main/5.png "Example Screenshot of a Level")  
---

Example Screenshot of a Level
![Example Screenshot of a Level](https://github.com/M64GitHub/TRILOGY/blob/main/6.png "Example Screenshot of a Level")  
---

Example Screenshot of a Level
![Example Screenshot of a Level](https://github.com/M64GitHub/TRILOGY/blob/main/7.png "Example Screenshot of a Level")  
---
