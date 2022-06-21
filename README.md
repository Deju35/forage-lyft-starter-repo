
The current service criteria are as follows:

Engines
Capulet Engine - should be serviced once every 30,000 miles, 

Willoughby Engine - should be serviced once every 60,000 miles, 

Sternman Engine - should be serviced only when the warning indicator is on

Batteries
Spindler Battery - should be serviced once every 2 years, 

Nubbin Battery - should be serviced once every 4 years, 


The first task is to convert the UML Diagram provided to source code, name the file carfactory.py


The second  task is to write unit tests for each of the battery and engine classes in the codebase 

The third task is to a--modify the Spindler battery so it requires service after three years instead of two.

b-- Add tire servicing criteria

There are two types of tires currently in use by the Lyft fleet - Carrigan tires and Octoprime tires. The new tire wear sensors produce an array of four numbers between 0 and 1 inclusive, representing how worn each of the tires are. This array will be passed to each function in the car factory class, to be used by your tire implementation. Carrigan tires should be serviced only when one or more of the values in the tire wear array is greater than or equal to 0.9. Octoprime tires should be serviced only when the sum of all values in the tire wear array is greater than or equal to 3
