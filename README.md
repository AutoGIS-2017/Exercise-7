# Exercise 7

This week we will practice how to work with OpenStreetMap data and conduct network analysis in Python.

- Exercise 7 is due by the start of lecture on 18.12.

- Don't forget to check out the [hints for this week's exercise](https://automating-gis-processes.github.io/2017/lessons/L7/exercise-7-hints.html) if you're having trouble.

- Scores on this exercise are out of 20 points.

## Problem 1 (8 points)

There exists two csv-files in the [/data](/data) folder. The files contain coordinates of the
origin and destination points in certain area in the world.

In the first problem you should:

 1. Find out the area where the points are located. **Where are points located (name of the region)? Write your answer here:**
 2. Retrieve OpenStreetMap data (streets that can be driven with car) from the area where the points are located
 3. Using the UTM projection: Plot the street network (gray color) and on top of that the origin points with red color and destination points with blue color.

Commit the changes to your script and upload it to your own GitHub repository for Exercise 7.

## Problem 2 (12 points)

In this problem we practice conducting shortest path routing.

In the second problem you should:

 1. Calculate the shortest paths between all origin points (16) and destination points (20) using the `distance` of the road segments as the impedance measure (in total 320 routes).
 2. Create a GeoDataFrame where you should store all the LineString geometries of the shortest path routes, and the distance of the route in meters.
 3. Plot all the routes on top of the street network.
 4. Calculate the total distance of all the routes (i.e. sum of all route distances)

    - **What is the total distance of all routes? Answer here:**

Commit the changes to your script and upload it to your own GitHub repository for Exercise 7.

