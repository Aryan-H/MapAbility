# MapAbility

Mapability is a Google maps clone created in C++ as apart of the ece297 curriculum. For plagarism purposes, the code is not visible in this repository but please feel free to contact me at aryanhussain240@gmail.com to get access to the code base.

Presentation Link: https://docs.google.com/presentation/d/1go6gdSBiyv9eRXCXB_X1wKZjhNgQJcIUrs9yGh8hdqU/edit?usp=sharing 

![27gif](https://github.com/user-attachments/assets/e9ce8c80-b018-4cca-a817-923930110874)

Pathfinding Algorithm: Mapability leverages Dijkstra's algorithm for initial pathfinding, which was later upgraded to the A* algorithm to improve efficiency and accuracy in navigation. The A* algorithm enhances the basic Dijkstra approach by incorporating heuristics to prioritize paths that are likely to lead to the destination more quickly. Additionally, the application features an autocomplete search bar implemented using a trie data structure, allowing for efficient and rapid search queries as users type. The user interface (UI) of Mapability was developed using GTK and CSS, providing a responsive and visually appealing design for seamless user interaction.

Travelling Salesman Problem: The Traveling Salesman Problem (TSP) is a classic optimization challenge where the goal is to find the shortest possible route that visits multiple points on a map. It is computationally hard because the number of possible routes increases factorially with the number of cities, making it impractical to solve exactly for large datasets. Our approach to solving TSP in Mapability involves a three-step process.

First, we precalculate all possible routes using multidestination Dijkstra and store them in a lookup table. To expedite this process, we utilized parallel processing, significantly reducing computation time. Second, we employed a greedy algorithm, which iteratively selects the next city based on the shortest available edge, testing different paths for 5000 iterations. Finally, we implemented a 2-opt algorithm, a local search method that iteratively swaps two edges to reduce the total path length, to refine the solution and find the best route within 50 seconds. This combination of techniques allows us to tackle the TSP efficiently, balancing accuracy and computational feasibility.

![27gif](https://github.com/user-attachments/assets/331c1f22-a87b-4307-8a4a-1845d37507e2)

Extra Feature - Multiple Langauges:
![lang](https://github.com/user-attachments/assets/34391f9d-d3be-4923-8780-af25162d08cd)

Extra Feature - Colorblind and Night Mode:
![cb](https://github.com/user-attachments/assets/85fbec33-d797-4e85-8857-d7378c41cd59)

Extra Feature - Subway Visibilty (Accessibilty Noted):
![subway](https://github.com/user-attachments/assets/59b87c6b-104c-437b-86d7-57f94b219b41)

Overall this was a fun project to make and I really appreciate you taking the time to look through this!

