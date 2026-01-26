# Week 3 Exercises

Consider a simple two-body system: a planet of mass $M_p$ and radius $R$, rotating at angular frequency $\Omega$, orbited by a satellite of mass $M_s$ on a Keplerian orbit with semi-major axis $a$ and eccentricity $e$. Assume $M_s\ll M_p$.

1. Write down the equation(s) required to compute the tidal deformation of the planet. Indicate where orbital eccentricity and planetary rotation enter the formulation.

2. Implement an algorithm to animate the deformation of the planet’s surface over several orbital periods. Show the behavior of this system with the following parameters:

    a. $e=0$ and $\Omega = 0$

    b. $e=0$ and $\Omega = n$

    c. $e=0.8$ and $\Omega = 3n$

3. (extra) Implement rotational deformation, assume the rotation is sufficiently small so that the tidal and rotational deformation effects add linearly.