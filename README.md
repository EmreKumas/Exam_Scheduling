This C project is built to **schedule exams** (in universities for example). It takes a text input file which *contains name and lessons* for every single person.

The program analyses the input file and determine an *appropriate exam scheduling* so for every person no exam will be *overlapping*. A common problem in universities since no person can enter *two exams at the same time*.

It uses *graph coloring algorithm*. Simply after reading the input file, it creates *vertexes* for every lesson. Then it makes *edges* between vertexes based on every single persons lessons. So if a vertex have an edge between another vertex then these vertexes won't be in the same exam program because they will be *overlapping*. After creating edges, the program outputs an *adjacency matrix* to show the relations between lessons. Based on this adjacency matrix the program visits every vertex using the DFS algorithm and *colors* every vertex appropriately. Then based on those colors, it creates *exam programs*.

If you are reading this file, most probably you know how to compile this C program and execute it. But if you don't know it, I have a *Wiki page* for you to be with US. **Visit it**.