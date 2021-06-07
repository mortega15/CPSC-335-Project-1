# CPSC-335 Project 1

__Group Members: Maria Ortega and__

                                        1. Introduction

For this project two algorithms were mathematically and experimentally analyzed. The three components that were considered for this project were:
1. A written mathematical analysis. 
2. Implementation of the algorithms in C++ (to specific C++17)
3. A written empirical analysis (graphs)

                                        2. Mathematical Analysis
For this part of the project,we looked at the two exercises 3-14(a) and 3-14(b). As seen below (a) dealt with finding the mean of a random list of numbers, while (b) dealt with finding the square matrix of an integer. 

![image](https://user-images.githubusercontent.com/79822470/120994724-9c0b9480-c739-11eb-888e-49b384c7dc86.png)
![image](https://user-images.githubusercontent.com/79822470/120995060-e856d480-c739-11eb-9a34-f8b10b58215a.png)

                                        3. Implementation in C++
For this part of the project, we simply implemented the concept of the two previous programs into actual C++ code. For this we took the pseudocode and translated it into working C++ code. For this project we had to make sure that we were utilizing C++17. One thing that both programs had to have was that they needed to generate problem instances of various sizes of _n_ and should record the time taken to run the algorithms every time. This was done using:
- std::rand() # used to generate values for the new problem instances (random problem instances)
- std::chrono # used to record the elapsed time (sec. for measurement)        
- std::vector<int> #used for L in (a)
- std::vector<std::vector<int>> # used in (b) for the n*n matrix


                                        4. Empirical Analysis

For this part of the project, we gathered and recorded some of timing data by running a few trials for each of the two problems. We record the values of _n_ that we used and the elapsed time in a excel sheet. Once the information was gathered, we generated a scatterplot with a trendline as to observed trials.
