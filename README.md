# Distance-Vector-Routing-and-Flow-Control-Simulator

The project simulates a network traffic in a given topology where the distance vector algorithm is used for path computations and routing.
The topology of the network is given and cannot be changed by the user. User can change the path costs between each router,
and specify any number of flows from any router to the other. Package size also can be changed.
After the user specifies, the program can run the network traffic.

The program basically consists of two major parts: 
                                                - Distance Vector Computation
                                                - Forwarding and Routing Algorithm

*Distance Vector Computation:*
* User inputs path costs between routers in a fixed network topology.
* The program calculates distance vectors based on the entered path costs.
* The computed distance vectors are then exported to a text file.

*Flow Routing Algorithm:*
* Utilizes the output of the Distance Vector Computation as input to construct the network topology.
* User specifies various parameters, such as packet flow details (source, destination, package sizes).
* The program simulates network traffic, considering factors like visited routers, queues, delays, etc., at each step of package transmission.


Used skills:
* Socket Programming: Used for communication between routers, facilitating the exchange of information.
* Multi-Threading: Implemented to enhance program efficiency and handle concurrent tasks.
* De-centralized Programming: The project involves decentralized programming techniques to simulate network behavior.
* Object-Oriented Design: The program is structured using object-oriented principles, enhancing modularity and maintainability.
* I/O Management, File Reading/Writing: Involves handling input/output operations, reading user inputs, and exporting computed data to files.
* Implementation of Algorithms: Involves the implementation of Distance Vector, Routing/Forwarding, and Flow Control Algorithms to simulate and manage network traffic effectively.
   
