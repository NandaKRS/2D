# 2D
2D A star for AUV

This program is taken from MATLAB tutorial, which can be taken from this URL https://uk.mathworks.com/matlabcentral/fileexchange/26248-a-a-star-search-for-path-planning-tutorial.

This 2D A* has Main program and with the functions as distance, minimum function, expand array, insert open and node index.

Distance function: has the formula for calculating the distance between two cartesian coordinates.

Minimum function: is to return the Node with minimum fn. This function takes the list OPEN as its input and returns the index of the  node that has the least cost.

Expand array: This function takes a node and returns the expanded list of successors,with the calculated fn values.The criteria being none of the successors are on the CLOSED list.

Insert Open: Function to Populate the OPEN LIST. OPEN LIST FORMAT.

Node Index : This function returns the index of the location of a node in the list OPEN.
