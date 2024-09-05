# DES-TransportSystem
In the course on Discre Event System (DES) at UFCG/Brazil we are asked for designing a simple system in order to apply the principles of supervisory control on DES. The problem descrition is as following: 

"A freight transport system consists of a circular track with 8 sections and 3 vehicles. Between each section there is a traffic light that controls the entry of a vehicle into the section. Except between sections 2 and 3.

For safety reasons, only one vehicle can travel in a section at a time.

Initially the vehicles are located in sections 1 (vehicle 1), 4 (vehicle 2) and 7 (vehicle 3)."

We solved this problem using the Supremica software as following:

* Creating 3 similar automatons for representing each vehicle;
* Setting boolean variables to represent if a state (section) is occuped or not;
* Creating a one-state automaton representing the specification;
* Synthesizing all automatons and variables to create a Supervisor.

 Authors: 

* Adeilson Leal
* Jackson Guedes
* Tobias Oliveira
