# Shortest-Path-AI

This repository contains a main.py file which either creates a random grid or takes a grid input and finds the shortest path using both the A* and Theta* algorithm. 

## A*

The A* huristic explores surrounding points of the current point and chooses the closest point based on the point's to the start node, and the distance to the end node. 

## Theta*

A very similar algorithm to A*, however instead of inrementing one gridspace at a time, Theta* saves past points up until there is no longer a line of sight point. 

## Advantages 

The advantages of both algorithms as apposed to using a dykstras or breadth first search is that the algorithms use much less memory with a scarifice of the probabiliy of small error. 