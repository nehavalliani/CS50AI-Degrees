# CS50AI-Degrees
Added AI functionality to identify the degree of separation between actors from the corpus.

# The Algorithm
AI was used to determine the degrees of separation between two actors, or to find the shortest path between any two actors by selecting a sequential order of movies in which they have starred. The corpus has 3 sets of data: 1. All people, 2. Movies, 3. Stars. The name of two actors is taken as input and by using the shortest path algorithm, the code searches for the common connections and returns the degree of separation between the two actors. 

Eg. if 
Name1: Tom Cruise
Name2: Sally Field

After searching for the shortest possible path between the two, the output on terminal is as follows:
2 degrees of separation.
1: Tom Cruise and Paul Newman starred in The Color of Money
2: Paul Newman and Sally Field starred in Absence of Malice

# How to Run
Download all files and run degrees.py
From the list of people available, enter names of 2 actors on the terminal (when asked) after the data is loaded
