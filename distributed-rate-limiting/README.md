Date: Tuesday April 3rd, 4:00
Place: Building 356, Room 109 
Speaker: Richard Ramsden (4th CSCI Student, Vancouver Island University)

Distributed Rate Limiting
-------------------------

Abstract
--------

The Distributed Rate Limiting (DRL) problem can be described as trying to distribute service capacity (“service rate”), expressed as a number of service requests per time interval, over
a group of N servers in such a way that the amount given to each server C_i is dependendant on the job population D_i at each server.
We want to find a fair distribution of the service rate such that (D_i / C_i) is equal at every server. Creating a distributed algorithm to solve
this problem is non-trivial since demand at each server is dynamic, i.e., changes with time. Furthermore, servers can fail for numerous reasons.
Designing an algorithm which adapts quickly to change and is fault-tolerant is the main contribution of my research.
The work presented in this talk comprises course work for a Directed Studies CSCI 485 under the supervision of Dr. David Wessels, in collaboration with Bravenet Media.
