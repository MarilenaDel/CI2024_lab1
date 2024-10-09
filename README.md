# CI2024_lab1
For the set covering problem, I implemented a Tabu search.  
I believe that, as a local search, this method helps avoid getting stuck in a local optimal solution, by using a tabu list to prevent revisiting previously found solutions.

I am aware that my solution is not the best possible one, as I am not very confident with Python and its tools, so I tried to follow the scheme of a pseudocode of Tabu search found online (https://en.wikipedia.org/wiki/Tabu_search#) and adapt it to the set covering problem.  
From my experience, I found that a reasonable value for the size of the tabu list (tenure) could be 5 for the first problem instances, up to 10 for the last one.
