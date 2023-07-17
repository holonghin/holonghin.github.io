# LINE FOLLOWING ROBOT

​																																																																						By Jonas Ho, Mike Ho

>  Line following system is an automated robot that can move along a black line or a magnetic field path drawn on a contrasting color surface. The system typically consists of the sensors installed at the front end of the robot and the wheels driven by the motors. These sensors detect changes on the chosen path to adjust the direction of the wheels, keeping the robot on the line. The line following system is commonly used in industrial automation, logistics transportation, environmental monitoring, and other fields.                                                                                                                                                                                                                                                    <img src=".\assets\fd55051c9122125f7617d4b29b5280481061b3eeLEGO-Mindstorms-EV3-Sterling-Lego-Submarine-Robot-Fllcasts-1678001916404-2.png" alt="fd55051c9122125f7617d4b29b5280481061b3eeLEGO-Mindstorms-EV3-Sterling-Lego-Submarine-Robot-Fllcasts" style="zoom:25%;" /> 
>
> EV3 line following robot

## Design

> In the design, I apply the genetic algorithms to calculate the best size of the robot, and use the calculating data to draw the 3D CAD in Fusion360.

###  I. Genetic Algorithms(GAs)

​	A genetic algorithm is a type of metaheuristic and evolutionary algorithm inspired by the process of natural selection. It is used in computer science and operations research to find approximate solutions to optimization and search problems.

  ![](.\assets\geneAlg.jpg)

If you want to know more, you can watch this video:

<iframe width="560" height="315" src="https://youtube.com/embed/cxweR4i0ejA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

> Genetic Algorithm Explanation, By David Stepanov

This is the simulator which applies the genetic algorithms

<img src=".\assets\geneticAlgGif.gif"  />  

###  II. 3D CAD

​	

| <img src=".\assets\top2.png" alt="top2" style="zoom: 33%;" /> | <img src=".\assets\home2.png" alt="home2" style="zoom:33%;" /> |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
|                             TOP                              |                              3D                              |
| <img src=".\assets\front2.png" alt="front2" style="zoom: 33%;" /> | <img src=".\assets\right2.png" alt="right2" style="zoom: 33%;" /> |
|                            FRONT                             |                            RIGNT                             |

### III. PCB

> I design two PCB for the robot ----- sensor board and main control board

#### Sensor Board

