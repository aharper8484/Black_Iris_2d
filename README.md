# Black_Iris_2d
Tense 2D top down retro arcade game

A weaponless, resourceful marine must navigate corridors to activate 3 triggers that enable an escape

Obstacles:

- Aliens of varying intelligence/strength
- A torch that drains in power, reducing visibility and risk

Torch:
Obscures the grid with a radius that shrinks in size after an alloted amount of time. Collecting a battery resets the timer and expands the view to allow marines to see aliens etc. If the batteries die then it is instant death for the marine

Energy:
Contains a value of levelling up (low, med, high for example) which restores marines health

Collect:
- Energy
- Battery for torch
- Freeze (alien pauses for number of moves 1, 2 or 3?)

Map:
- Predetermined grid to start
    - Randomly generate in future
- 3 tile types to start (vertical, horizontal, crossroads)
    - Expand in future (open spaces, locked doors - lose 1 move - and dead ends etc)
- Anything outside of grid pieces are black and serve no function

Marine:
- Moves one direction at a time (4 directions)
- Has 5 lives, can collect energy to restore - encountering an alien reduces energy by set amount (based on different aliens?)
- Has torch radius the can expand/shrink

- Actions:
    - Stand still
    - Walk up, down, left, right
    - Open door
    - Collect item
    - Injury (alien)
    - Die (alien, battery)
    - Battery (can cause death)
    - Escape

Alien:
- Moves one direction at same time as Marine (random to begin)

- Actions:
    - Move - any direction
    - Intelligence - dictates the type of movement
    - Speed - may move more than one space at a time, or every two turns if slow
    - Eat - will cancel any collectable items if they pass over them

# Questions

- Is the grid a set shape or size? Or will it develop as a marine moves within it?
- How will view adapt to expanding map and shrinking visibility
- Should there be a radar to emit the direction of the exit once it is enabled?
