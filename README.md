# 3D Trapping Rain Water System
The repo contains the solution to the complex 3D rain water trapping system which was presented in Leetcode Problem No. 407 and Google Interview Round. Additionally, it treats '0' as the drainage of the system. (Check the readme file for detailed description)

## Problem Statement
There is a partially constructed platform floating in space which is made of cubes. The platform can be represented by 2D array with each element representing number of cubes in respective position. 

The way the platform is piled up, is given by an n x m matrix, where each element says how many cubes are stacked upward in that position. You have to write a function for calculating the quantity of water which will be stored in that construction if we pour unlimited supply of water on top of it. 
*Since the platform is suspended in space, if an element has **0** as one of the elements, it will represent a drain.*

## Examples 

Example I:

[2 . 2 . 2]

[2 . 2 . 2]

[2 . 2 . 2]

Indicates a cuboid of 3x3 area units, which cannot retain any amount of water (0 units of water retained)

