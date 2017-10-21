# Implementation of hill climbing algorithm with simulated annealing in python

In this implementation the algorithm is searching for the most efficient tour to visit a number of cities.

**Cities:** A, B, C

**Distances between Cities:**

| |A|B|C|
|-|-|-|-|
|**A**|0|3|2|
|**B**|3|0|1|
|**C**|2|1|0|

**Possible Tours:**

 **A** --[3 km]--> **B** --[1 km]--> **C** | **[4 km]**

 **A** --[2 km]--> **C** --[1 km]--> **B** | **[3 km]** (most efficient)
 

**propability calculation** for simulated annealing: ![asd](http://latex.codecogs.com/png.latex?%5Cdpi%7B200%7D%20e%5E%7B%5Cfrac%7BcurrentFitness%20-%20lastFitness%7D%7Btemperature%7D%7D)

If you change the amount of cities (countCities = x), you have to change the temperature aswell. You have to experiment with the epsilon value and the value for temperature. Remember, epsilon should be small!


