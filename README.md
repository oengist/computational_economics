# computational_economics

This repository contains my final project for "computational economics" at Chapman University, Fall Semester 2015.
It is written in Wolfram Mathematica.

The program solves the stochastic job shop scheduling with multiple workers by using dynamic programming.
It decides whether to accept or decline a job and how to split it over (homogenous) workers by calculating the
highest expected values given the remaining workers and the probabilities of future jobs.

The second part of the program solves the problem as if we had perfect foresight about which jobs will arrive in the future.
In the output I compare the performance of the stochastic dynamic program to the program with perfect foresight.
