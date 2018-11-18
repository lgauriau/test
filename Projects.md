# Engineering projects done at school :

</br></br>

| Name | Summary | 
| :-------: | :------ |
| [Pyrat](#pyrat) | Python algorithm implemented to move a rat on a fixed maze </br>(Similar scenario as a PacMan game) |
| [DEC Project](#dec-project) | Creation of a robot vehicle with Arduino microcontroller |
| [DEV Project](#dev-project)  | Installation and design of 32 Raspberry PI server |
| [Network Prog](#network-prog)  | Creation of a protocol Specification </br> Python code implemented using a Framework and shared with Git |
| [DB project](#database-project)  | Implementation to manage a library with a database </br> and an access layer using an existing GUI </br>  |
| [Gambling Site](#gambling-site)  | Implementation of a Gambling Site from scratch, using V-cycle production  |

</br></br>

<h2>Pyrat</h2>

This project was part of computer sciences class. It was a first year project, made to deepen python knowledge.
The purpose of the project was to optimize the route of a rat moving on a 
maze to catch pieces of cheese randomly placed on a fixed-size maze.
I implemented a python algorithm using usual maze resolution algorithm models. 
Then i took part into a competition to select the fastest algorithm.
Several parts were tackled :
* Mathematical maze resolution
* Understanding of usual algorithms (Backtracking, Dijkstra...) and implementation applied to the scenario
* Glimpse of code optimisation techniques

One of my mistake was not to explore other algorithms possibilities. I chose to implement one of the algorithms seen in class 
instead of being more curious. Then i pushed the limits of this algorithm not regarding other methods. 
That's the main reason why i didn't win the competition.


<h2>DEC Project</h2>

It was made on my first year in IMT. I was part of a multicultural group working together to create a robot
using an Arduino card. The purpose was to win a race against other students.
Each of us split on different tasks. I took part in the design creation for the robot. 
After balancing between aesthetic and performance
i designed the blueprint on Cura, and printed in 3d the shell of our vehicle.

<h2>DEV Project</h2>

The topic was a suggestion from a teacher for our group. He's teaching Big Data in IMT to 3rd year students. He's using a 32 Raspberry PI 
server in class and wanted us to reorganise the pi's in order to be easily carried and 
then install Docker on each cards. What we did :
* Design a box to carry the server from class to class plug with one ethernet (using switch) and deliver power supply from one plug
* Install Raspbian on the PI's
* List IP adresses using Putty
* Attempt to install Docker

We didn't achieve Docker installation due to incompatibility with Raspbian. However, it was a great introduction to understand how a server is implemented, even if we lacked some useful knowledges to fullfill the last objective.

<h2>Network Project</h2>

I worked in group to specify a network protocol to satisfy requirements for a Chat application. After presenting specifications made by other groups showing the pros and cons, we implemented the specification made by the teaching staff. We used python and Twisted framework, and shared our work on a Redmine server using Git. We only implemented communication protocol in order to use an existent <abbr title="Graphical User Interface">GUI</abbr> and the server. The code worked on both <abbr title="User Datagram Protocol">UDP</abbr> or <abbr title="Transomission Control Protocol">TCP</abbr>.

<h2>Database Project</h2>

This project was made to deliver a working <abbr title="Graphical User Interface">GUI</abbr> to manage a library database. First i built a database using schemes to write an SQL script. Then the main part was to complete a Java code using PostGreSQL queries, to check every functions asked to run a library.

<h2>Gambling Site</h2>
