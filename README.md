# haxu0278_9103_Som
My first repository for IDEA9103

This is my first local change to the repo!

May 1st: p5_project_Monalisa

May 8th: Quiz8

## Part 1: Imaging Technique Inspiration
**Chosen Example:** Ivan Rudnicki's "Puzzle Pieces".
I chose this interactive puzzle artwork because of its playful logic. The image is broken into scattered pieces. What I really love is the interaction: when you click a piece, it usually snaps to its correct position, but there's also a small probability it will fly off randomly. You can even click on already assembled pieces to detach them. I want to incorporate this specific "snap-and-detach" mechanic and this slight unpredictability into my project. It transforms static visual data into a game-like experience, making it much more engaging to interact with.
### Screenshots:
![Puzzle State: Disassembled and Scattered](Quiz%208/PARTLY_ASSEMBLED.png)
![Puzzle State: Fully Assembled](Quiz%208/FULLY_ASSEMBLED.png)

## Part 2: Coding Technique Summary
To achieve this effect, I will explore Object-Oriented Programming (OOP) and state toggling. Each puzzle piece acts as an independent object instance, managing its own data like current position, home coordinates, and a boolean state (inplace). The core interaction relies on bounding-box collision detection during mouse clicks. Instead of complex physics, clicking a piece simply toggles its state, updating its target coordinates to either its original grid location or a randomized scattered position. Finally, the code uses linear interpolation (lerp()) to smoothly animate the pieces moving and rotating toward their new target destinations.
### Screenshots:
![The coding technique in action](Quiz%208/PARTLY_ASSEMBLED.png)
### Link:
[Click here to view the OpenProcessing sketch](https://openprocessing.org/sketch/2847358)