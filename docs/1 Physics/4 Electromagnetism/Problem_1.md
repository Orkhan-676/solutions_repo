# Problem 1
# **Problem 1: Simulating the Effects of the Lorentz Force**  


## **Introduction**
The **Lorentz force** governs how charged particles move in electric and magnetic fields, playing a central role in systems such as particle accelerators, mass spectrometers, and plasma traps.
This problem investigates the motion of a single charged particle under various configurations of **electric** (𝐸) and **magnetic** (B) fields.
Through simulation, we visualize key physical behaviors such as **circular motion, helical trajectories, and E×B drift.**



## **Theoretical Background**
## Lorentz Force Equation
The force acting on a charged particle is defined by:


Where:



From Newton’s second law:


we can iteratively compute the particle’s velocity and position.

## **Computational Simulation**



4. Field Configurations and Trajectories
1. Uniform Magnetic Field
𝐸
⃗
=
0
,
𝐵
⃗
=
(
0
,
0
,
1
×
10
−
3
)
 T
E
 =0, 
B
 =(0,0,1×10 
−3
 ) T
Initial velocity:

𝑣
⃗
0
=
(
1
×
10
5
,
 
0
,
 
0
)
 m/s
v
  
0
​
 =(1×10 
5
 , 0, 0) m/s
2. Electric and Magnetic Fields Combined
𝐸
⃗
=
(
1
×
10
3
,
 
0
,
 
0
)
 V/m
E
 =(1×10 
3
 , 0, 0) V/m
3. Crossed Fields
𝐸
⃗
=
(
0
,
 
1
×
10
3
,
 
0
)
,
𝐵
⃗
=
(
0
,
 
0
,
 
1
×
10
−
3
)
E
 =(0, 1×10 
3
 , 0), 
B
 =(0, 0, 1×10 
−3
 )



**Observed Phenomena**
-**Circular Motion**

 Occurs under a uniform magnetic field with perpendicular velocity.

 Radius of curvature (Larmor radius):

𝑟
𝐿
=
𝑚
𝑣
∣
𝑞
𝐵
∣
r 
L
​
 = 
∣qB∣
mv
​
 
Helical Motion

Happens when there's velocity along the magnetic field direction.

E × B Drift

In crossed fields, the particle drifts perpendicular to both 
𝐸
⃗
E
  and 
𝐵
⃗
B
 :

𝑣
⃗
𝑑
=
𝐸
⃗
×
𝐵
⃗
𝐵
2
v
  
d
​
 = 
B 
2
 
E
 × 
B
 
​
 
## **Conclusion**
This simulation provides insight into the motion of charged particles under electromagnetic forces.
Key dynamics such as **Larmor radius, helical paths, and drift velocity** illustrate fundamental principles behind real-world systems like accelerators and magnetic traps.
