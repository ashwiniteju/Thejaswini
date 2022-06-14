# Thejaswini
assessment
Problem Statement: We have an NxM grid, grid have one element named Bob. Bob can travel diagonally blocks only. The grid has some blocked blocks on which Bob can not travel. Write a function that returns on how many possible positions Bob can move. Solve this problem using BFS and submit the executable code in any programming language. In the following image example, Bob's positioning is at 9,3, and it can visit the places where Y is marked; hence your method should return 31. *

Basic Logic:

Bob Travel only diagonally and only where Y is and have to find number of postions he can go using BFS traverse method 1 First I have converted given path into two dimensional array. 2.found first position of diagonal entities. 3. Made new array in which i have stored where bob has visited already. intially all entities are unvisited. 4.while loop will run until the Array named Bob_enqueue (bob is visiting) get zero; 5.there is one more array tempArr which is actully deque of BFS search, it stores the entities whose child nodes are already been searched. 6.there are several conditions like end node in Array where program has to find only two diagonal entites Hence the conditions where (node==Last_NODE) (position==0) (node==0) (position==Last_POSITION)
