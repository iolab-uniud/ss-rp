# Slab Selection and Relocation Problem with Piling Rules

This repository contains instances and best solutions for the Slab Selection and Relocation Problem proposed in the paper "Solving the Slab Selection and Relocation Problem in a Real Production Yard using Simulated Annealing" by Antonio Cardin, Sara Ceschia, Andrea Schaerf, Davide Armellini and Paolo Borzone (submitted for publication).

In addition, it contains our best solutions of the dataset AC for the Blocks Relocation Problem with Item Families proposed by [Boge and Knust (2023)](https://doi.org/10.1007/s00291-022-00703-x), available at [https://www2.informatik.uos.de/kombopt/data/brpif/](https://www2.informatik.uos.de/kombopt/data/brpif/).

Instances and solutions are in text-only format. Instances of dataset DA are complemented by the following constant values for the parameters not written in the instance file:

* H = 3840 (maximum height of a stack in mm)
* P = 33000 (maximum pressure in Kg/m^2)
* abs_delta_l = 2000 (maximum length difference between two slabs in the same stack in mm)
* rel_delta_l = 1500 (maximum length difference between two consecutive slabs in the same stack in mm)
* rel_delta_w = 300 (maximum width difference between two consecutive slabs in the same stack in mm)
* V_x = 2.90 (velocity of the crane along the x axis in m/s^2)
* V_y = 1.60 (velocity of the crane along the y axis in m/s^2)
* A = 5 (dimensional tolerance used to define candidate slabs of a generic order in %)
* P_t = 25 (fixed time needed to either attach or detach a slab to the crane in s)

The solutions reports the list of selections of slabs for the orders, followed by the sequence of movements, denoted by the source and destination stacks (or OUT for retrieval). The moved slab is implicitly the topmost of the stack.
