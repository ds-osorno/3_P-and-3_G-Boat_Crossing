# 3 Priests and 3 Ghosts Boat Crossing Puzzle

## Problem Statement

You are on one side of a river, and you need to transport 3 priests and 3 ghosts to the other side of the river using a small boat. However, there are certain rules and constraints you must follow:

1. The boat can only carry a maximum of 2 passengers at a time.
2. At no point on either side of the river should the number of ghosts exceed the number of priests. Otherwise, the ghosts will outnumber the priests, and it's considered unsafe.

Your task is to find a series of boat trips that will safely transport all 3 priests and 3 ghosts from one side of the river to the other, adhering to the above rules and constraints.

## Rules and Constraints

- The boat can carry a maximum of 2 passengers at a time.
- The number of ghosts on one side of the river should never exceed the number of priests on that side.

## Objective

The objective is to find a sequence of boat trips that will safely transport all 3 priests and 3 ghosts from one side of the river to the other while adhering to the rules and constraints.

## Example

Here is one possible solution:

1. Take 2 priests to the other side. (Current state: 1 priest, 3 ghosts on the starting side)
2. Return alone to the starting side. (Current state: 2 priests, 3 ghosts on the starting side)
3. Take 2 ghosts to the other side. (Current state: 2 priests, 1 ghost on the starting side)
4. Take 1 priest and 1 ghost back to the starting side. (Current state: 1 priest, 2 ghosts on the starting side)
5. Take 2 priests to the other side. (Current state: 0 priests, 2 ghosts on the starting side)
6. Return alone to the starting side. (Current state: 2 priests, 2 ghosts on the starting side)
7. Take 2 ghosts to the other side. (Current state: 2 priests, 0 ghosts on the starting side)
8. Take 1 priest and 1 ghost back to the starting side. (Current state: 1 priest, 1 ghost on the starting side)
9. Take 2 priests to the other side. (Current state: 0 priests, 1 ghost on the starting side)
10. Return alone to the starting side. (Current state: 2 priests, 1 ghost on the starting side)
11. Take 2 ghosts to the other side. (Current state: 2 priests, 0 ghosts on the starting side)
12. Return alone to the starting side. (Current state: 3 priests, 0 ghosts on the starting side)

Now, all 3 priests and 3 ghosts have safely crossed the river.



This puzzle is a classic example of a river-crossing puzzle, where you need to devise a strategy to transport a group of individuals across a river while respecting specific constraints. The objective is not only to find a solution but also to find the most efficient one, minimizing the number of boat trips.
