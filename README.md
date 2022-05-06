# Introduction
13.8 billion years ago, since the Big Bang, the universe has been the totality of existence, containing the entirety of space and time, as well as their contents. Within these contents, exist four fundamental forces, being **Weak Nuclear force**, **Strong Nuclear force**,**Electromagnetic force** and **Gravitational force.**

Every physical phenomenon we observe, from a sub-atomic to a universal scale, is all the result of the interaction of these four fundamental forces with matter, at different scales, at different intensities. The most abundant of these forces is the **Gravitational force**. Gravitational force (or gravity) is the attraction between two objects with mass or energy. Gravity is responsible for objects falling towards the surface, the tides caused by the orbiting of moon around the Earth, and even holding the solar system and galaxies together.

Just like any other force, the gravitational force acting on each object changes as new objects with mass and energy enter its range. This is the result of vector addition of gravitational force and to compute and calculate the motion of objects under the influence of each other’s gravity is known as the ***n-body problem***.

# N-Body problem
The n-body problem in physics is the problem of predicting the individual motions of a set of astronomical objects interacting gravitationally with each other. First posed by Sir Issac Newton, this problem specializes in the motion of objects due to the gravitational interaction between them. This problem, with combination with general relativity, has been instrumental in predicting the interactions of many astronomical structures.

The n-body problem considers n point masses *m<sub>i</sub>, i = 1, 2, . . . , n* in an inertial reference frame in three dimensional space R3 moving under the influence of mutual gravitational attraction. The general formula for this problem is

<p align="center"><img  width="320" height="80" src = "https://github.com/aaryannagpal/n-Body-Problem/blob/main/Images/Newtons%20Law%20of%20Attraction.jpg?raw=true"></p>

where _G_ is the gravitational constant and *||q<sub>j</sub> − q<sub>i</sub>||* is the magnitude of the distance between *q<sub>i</sub>* and *q<sub>j</sub>* .

## Leapfrog Integration Method
In numerical analysis, leapfrog integration is a method for numerically integrating differential equations of the form

<p align="center"><img  width="200" height="80" src = "https://github.com/aaryannagpal/n-Body-Problem/blob/main/Images/Double%20Derivative.jpg?raw=true"></p>

We use this method in Jupyter Notebook to present the n-body problem as it does not take much space in memory during the simulation.
We use the following formula:
<p align="center"><img  width="210" height="45" src = "https://github.com/aaryannagpal/n-Body-Problem/blob/main/Images/Leapfrog.jpg?raw=true"></p>

# N-body Simulation
In my project, I used the n-body problem to show the orbital movements of the planets, using the Leapfrog Integration Method. 

Using various simulations, the project explains the different cases of the n-body problem, using the example of objects in our own solar system. We will use the VPython module to represent our simulation.

## Two Body Problem
This is a special case of n-body problem that is the interaction between 2 bodies. It represents the case where there are no external force acting between 2 objects.
<p align="center"><img  width="190" height="150" src = "https://github.com/aaryannagpal/n-Body-Problem/blob/main/Images/es%20(1).jpg?raw=true"></p>
Here, we see the orbit of Earth and Sun, showing the interaction between them
in reality.

## Three Body Problem
This is a special case of n-body problem that is the interaction between 3 bodies. It represents the case where there is another body acting between 3 objects.
<p align="center"><img  width="200" height="150" src = "https://github.com/aaryannagpal/n-Body-Problem/blob/main/Images/ej.jpg?raw=true"></p>

Here, we see the orbit of Earth, Jupiter and Sun, showing the interaction between them in reality.

_**To implement this problem, refer to the Python Code**_
