# LCP_ModA_project
Authors: Maria Camila Paris Diaz, Arina Ponomareva, Marco Tavis Foster, and Lorenzo Martinelli.

Project for the first half of the course Laboratory of Computational Physics, part of the master's degree cycle in Physics of Data delivered at UNIPD.


## Outline
This project's main goal is to produce a highly-accurate simulation of an electron-positron scattering producing a muon-antimuon pair. The dynamics of the process involves a beam of positrons being shot onto a stationary (in the laboratory frame) target, leading to the emergence of a muonic pair due to the energy of the center of mass of the system being roughly the same as the mass of the emerging particles.
The whole project has been carried out in Python and it is articulated in six main sections:
* Compute the leading-order cross section as a function of the scattering angle, using the energy of the center of mass as a parameter.
* Compute the angular and momentum distribution of the emerging muonic pair.
* Change the frame of reference from the center of mass frame to the laboratory one.
* Automatize the simulation and produce a synthetic DataFrame of events.
* Estimate how many events one can simulate in a week of continuous operations.
* Introduce a couple of higher order effects into account: A different geometric energy profile for the beam, as well as the loss of energy of said beam in the target.

The results have been compared with a high-level simulation done with the BabaYaga tool developed by C.M. Carloni Calame, G. Montagna, O. Nicrosini, F. Piccinini at the INFN center of Pavia.
