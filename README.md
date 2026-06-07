Through this project, I am exploring how different numerical integration methods can be used to simulate planetary motion.

Planetary motion seeemed like a good system to work with bc it is simple to model but it still gives a lot of interesting things to analyse. Since the same physical system can be solved using multiple numerical methods, it provides a straightforward way to compare their accuracy and stability.

I am starting with a simple two-body system consisting of a star and a planet. The methods I plan to compare are:

- Euler Method
- Heun Method
- Fourth-Order Runge-Kutta (RK4)
- Leapfrog Method

The things I want to investigate are:

- How accurately each method reproduces orbital motion
- Energy conservation over long simulations
- Long-term numerical stability
- The effect of timestep size on the solution
- Verification of Kepler's Laws
- Comparison with real exoplanet data

I've heard RK4 and Leapfrog get mentioned a lot whenever orbital simulations come up, so I wanted to see what makes them so different from simpler methods like Euler's Method, and so i thought it'd be interesting to compare them on the same problem and see how they behave.
