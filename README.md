# TSP Genetic Algorithm

This project aims to solve the Traveling Salesman Problem (TSP) using a genetic algorithm. The TSP involves finding the most efficient route that visits a set of destinations and returns to the starting location. While finding the globally optimal solution for the TSP is computationally challenging, genetic algorithms offer an approximation approach to tackle such NP-hard problems.

## Problem Statement

You are given a list of destinations in Los Angeles along with their latitude and longitude (in degrees). Your goal is to visit all the destinations and return to your starting location efficiently (as defined by an objective function that we will specify and you will implement). The first location in the list read in from the text file is LAX, which will be your starting and finishing location.

## Genetic Algorithms Overview

Genetic Algorithms are a method for solving optimization problems based on natural selection. It tracks pretty closely to the tenets of Darwinism. In Darwinism, given some variation in genetic traits for some population, the members of that species with desirable genetic traits will survive more often and reproduce more, passing those genetics down, and thus, over generations, the desirable genetics will have larger market share.

The basic setup of a genetic algorithm is largely the same. Given some NP-hard problem, we don't assume to have any intuition about the "desirable traits" of a potential solution, so we generate some initial set of candidate solutions randomly. These solutions are a set of valid paths that begin at LAX, visit every node, and don't visit any node more than once*.


## Project Implementation

The goal of this project is to implement and assemble the components of a genetic algorithm to find "good" solutions for efficiently traversing the graph of Los Angeles. By iteratively improving candidate solutions through selection, crossover, and mutation, the algorithm aims to approximate the optimal solution for the TSP.

Please refer to the source code and accompanying documentation for detailed implementation instructions and further understanding of the genetic algorithm for the TSP.
