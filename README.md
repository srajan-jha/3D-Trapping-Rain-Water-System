# 3D Trapping Rain Water System
The repo contains the solution to the complex 3D rain water trapping system which was presented in Leetcode Problem No. 407 and Google Interview Round. Additionally, it treats '0' as the drainage of the system. (Check the readme file for detailed description)

## Problem Statement
There is a partially constructed platform floating in space which is made of cubes. The platform can be represented by 2D array with each element representing number of cubes in respective position. 

The way the platform is piled up, is given by an n x m matrix, where each element says how many cubes are stacked upward in that position. You have to write a function for calculating the quantity of water which will be stored in that construction if we pour unlimited supply of water on top of it. 
*Since the platform is suspended in space, if an element has **0** as one of the elements, it will represent a drain.*

## Examples 

### Example I:

[2 . 2 . 2]

[2 . 2 . 2]

[2 . 2 . 2]

Indicates a cuboid of 3x3 area units, which cannot retain any amount of water (0 units of water retained)


### Example II:

A 4x3 matrix like the following

[2 . 2 . 2 . 2]

[2 . 1 . 2 . 1]

[2 . 2 . 2 . 1]

The 1 area in the middle stores 1 unit of water. The 1 area on the sides will retain no water as the water will spill out. Hence this structure will hold 1 unit of water II.


### Example III:

A 6x4 matrix like the following

[3 . 3 . 3 . 3 . 3 . 3]

[3 . 1 . 2 . 3 . 1 . 3]

[3 . 1 . 2 . 3 . 1 . 3]

[3 . 3 . 3 . 1 . 3 . 3]

Can be represented as the 3D view shown. The second column stores 4 units, the third column stores 2 units and the fifth column stores 4 units of water. This matrix stores 10 units of water in total.


### Example IV:

A 6x4 matrix like the following
 
[3 . 3 . 3 . 3 . 5 . 3]

[3 . 0 . 2 . 3 . 1 . 3]

[3 . 1 . 2 . 3 . 1 . 3]

[3 . 3 . 3 . 1 . 3 . 3]

Can be represented as the 3D shown. This matrix resembles the example as the previous example. However, one of the elements on the second column has a 0 element. Since the structure is floating in space, the water poured would be drained out from this element. Hence the structure won’t be able to store any units of water on either the second or third columns. The only column water can be stores in is the fifth column which holds 4 units of water. Therefore this matrix holds 4 units of water in total.


### Example V:

A 5x5 matrix as the following

[ 5 . 5 . 5 . 5 . 5]

[ 9 . 1 . 1 . 1 . 5]

[ 5 . 1 . 5 . 1 . 5]

[ 5 . 1 . 1 . 1 . 5]

[ 5 . 5 . 5 . 5 . 5]

Will hold 32 units of water in total, as the second column will hold 12 units, the third column will told 8 units and the fourth column will hold 12 units, which adds up to 32 units in total.
