# Knapsack Problem Solver
This C# program solves the classic Knapsack Problem using dynamic programming. Given a set of items with weights, values, and a maximum capacity for a container, the program determines the optimal selection of items to maximize the total value while respecting the weight constraint.

## Problem Description
Consider the following items:

* Tablet: weight - 8, value - 50
* Camera: weight - 6, value - 150
* Laptop: weight - 6, value - 210
* Headphones: weight - 1, value - 30

The total capacity of the container is 10 kgs.

## How the Program Works
**1. Initialization:** Initialize arrays for weights, values, item names, and a 2D array to store intermediate results.

**2. Dynamic Programming:** The GetMaxValueInContainer method uses dynamic programming to fill the data array with the maximum values possible for different capacities and item selections.

**3. Output:** The program then outputs the maximum value achievable and the items to be included in the container, highlighting exclusions and inclusions.

## Running the Program
1. Clone or download the repository.
2. Open the solution in Visual Studio or compile the program using dotnet build.
3. Run the program to see the optimal solution for the given items and constraints.

## Example Output
Max value of items included in container: 240
Items excluded from the container are printed with a red background, while items included are printed with a green background.

## Notes
This program demonstrates a basic implementation of the Knapsack Problem using dynamic programming in C#.
Feel free to extend or modify the code for different items, constraints, or optimization criteria.

## ScreenShot
![Output](https://github.com/user-attachments/assets/37da5818-5afc-448d-9194-2ef806198c65)
