# Pendulum and Double Compound Pendulum Simulation

There are two files representing the simulation of movements of two different systems: simple pendulum and double-compound pendulum.

## Pendulum.ipnyb

Given a mathematical pendulum consisting of a rigid rod of length <img src="https://render.githubusercontent.com/render/math?math=l">, negligibly small mass, at the end of which is a small ball of mass <img src="https://render.githubusercontent.com/render/math?math=m">. The system is located in the constant gravitational field of the Earth. 

The first part of the file is dedicated to the simulation of free oscillations under constraint. Using the Lagrange approach, the equations of motion are derived and presented in the form of a system of differential equations. Constraint stabilization method was used. 

The case of forced oscillations was then simulated for the same mathematical pendulum. It is assumed that there is an actuator at the hanging point that provides a certain periodic moment that represents a generalized force. Also, it was assumed that the ball is subjected to a resistance force in the form <img src="https://render.githubusercontent.com/render/math?math=F_{ot}=-b\vec{v}"> during movement, where <img src="https://render.githubusercontent.com/render/math?math=\vec{v}"> is the linear velocity of the ball, and <img src="https://render.githubusercontent.com/render/math?math=b"> is the coefficient of resistance. The movement is simulated under two different moments: <img src="https://render.githubusercontent.com/render/math?math=M_1 =M_0\cos{\Omega t}"> (where <img src="https://render.githubusercontent.com/render/math?math=M_0"> and <img src="https://render.githubusercontent.com/render/math?math=\Omega"> are arbitary chosen amplitude of the moment and frequency, respectively) and <img src="https://render.githubusercontent.com/render/math?math=M_2"> represented by the square periodic signal.

The last part is dedicated to determining and comparing the amplitude characteristics of a pendulum moving under moments <img src="https://render.githubusercontent.com/render/math?math=M_1"> and <img src="https://render.githubusercontent.com/render/math?math=M_2">.

## Double-Compound-Pendulum.ipnyb

In this file, a simulation for a robotic two-segment mechanism is given. The given mechanism consists of two joints and two rigid connections in the form of homogeneous rods of masses <img src="https://render.githubusercontent.com/render/math?math=m_1"> and <img src="https://render.githubusercontent.com/render/math?math=m_2"> and lengths <img src="https://render.githubusercontent.com/render/math?math=l_1"> and <img src="https://render.githubusercontent.com/render/math?math=l_2">. The first joint is the active joint in which the actuator is located, which is the moment <img src="https://render.githubusercontent.com/render/math?math=M">. The second joint is a passive connection. The system is located in the constant gravitational field of the Earth.

Using the Lagrange approach, assuming the existence of a moment in the first joint, the equations of motion of this mechanism in the form of a system of differential equations are compiled.
