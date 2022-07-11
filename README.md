# VBA_Challenge

## Overview of Project 

VBA Challenge was a stock analysis to assist a financial advisor help his parents decide what stocks to invest in. The original code worked well for just a few stocks but needed fine tuned to work well for larger quantities of stocks. Since there was a base code there it would be more effecient to fine tune or refactor the code to make it run quicker and cover much larger data sets.

## Results

By refactoring this code we were able to take the generalized code that seached for specific things and give it perameters that allowed it to skip or ignore data we didn't need. This increased the speed of the run time for our code significantly. To do this we incorporated a variable to track which ticker we were on and then refrenced it with arrays to store the data we needed, linking it to the ticker it belonged to.

## Summary

Refactoring code can help streamline processes and improve exisiting code. Its especially good when you are taking a process from specific to generalized. Difficulties may arrise when multiple people are working on the same code or if you are working on refactoring someone elses code. This is due to following different thought processes. If the code is not well commented existing tools may be ignored causing inefficiencies or potential bugs in the program.

With regard to the original code for this it worked well because it was giving specific output for a single ticker. Making references in the code easy to direct to specific answers and calculations. However, it was not easily generalizable. This is due to the fact that it took almost a second for the single result, which when done in a table with thousands of results could easily add up. Through our refactoring we gave the code the tools to take in data store it to arrays which could be used to pull that data back up at a later time, requiring less overall memory usage at any given time and allowing the program to move more smoothly through the program without having to hold onto all the values it accumulated.
