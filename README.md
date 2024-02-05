An LTSpice simulation of an analog computer that simulates a single Qubit. 

A qubit is represented by two complex numbers, alpha and beta.  The inputs are the rate of change of angles of 
-Imaginary plane rotation (phi)
-Angle determining the lengths of alpha and beta (assuming alpha^2 + beta^2 = 1), thus they can be seen as sin and cos of some angle theta. 

It outputs the x,y,z coordinates on teh bloch sphere, and produces a signal of discrete +,- values which represent continuously measuring the qubit (a real qubit can only be measured once).  The values of the signal are according to the distrubtion as defined by the qubit.  This is given by the z coordinate of the position on the bloch sphere.

By Jae F. Muzzin for my medium article https://medium.com/@jaemuzzin
