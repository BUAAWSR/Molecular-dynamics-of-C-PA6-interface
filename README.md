# Molecular dynamics of C/PA6 interface

## Author
* Shenru Wang
* Xin Yan

## Description

This is a presentation regarding my previous work. The purpose of this project is to explore the temperature effect during the 3D printing process on the interfacial properties between continuous carbon fiber and nylon6 through molecular dynamics simulations. The carbon fiber is represented using a five-layer graphene model.

The project is  performed using Large-scale Atomic Molecular Massively Parallel Simulator (LAMMPS), and it encompasses five folders.

* "1-graphene equilibrium" contains program about the equilibrium of the graphene model.

* "2-nylon6 equilibrium" contains program about the equilibrium of the nylon6 model.

* "3-forming process" contains program about the simulation of interface forming process between graphene and nylon6 model. The interface is formed at different forming temperatures (450K, 475K, 500K, 525K, and 550K).

* "4-loading process1" contains program about the separation simulation of the interface model obtained from "3-forming process". This separation simulation is performed at a loading temperature of 300K. The interface model are prepared at different forming temperatures (450K, 475K, 500K, 525K, and 550K).

* "5-loading process2" contains program about the separation simulation of the interface model obtained from "3-forming process". This separation simulation uses the interface model prepared at 500K. The loading temperatures during the separation simulation are set as 300K, 330K, 360K, and 390K, respectively.

The detailed descriptions can be found in each "in" files.
