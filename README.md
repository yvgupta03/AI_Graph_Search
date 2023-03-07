# AI_Graph_Search
Refer to Project description file for detailed understanding of problem statement. Here I have implemented 5 different types of graph search algorithms for cliff-walker grid at shown below:

![image](https://user-images.githubusercontent.com/95063504/223298789-012cbd8e-5788-4639-9331-b86cf298eb22.png)

There are different utilities for each cell of the grid based on its color. The cheapest is white, green is expensive and red is basically death zone (or infinite cost). This project aims to study which search technique finds the best path with most reasonable search cost for finite cliff-walker grid, given a start and destination locations. 

The results have been visualized at the end of each notebook and A-star technique has the best performing heuristic that is reliable enough for such problems.
Each search technique is implemented in separate python notebook in python notebooks folder.
### Note :
The code base of each python notebook is flexible enough to accomodate your custom grid size as well as start-end locations and the results are backtracked to show the path according to the search technique applied. 
