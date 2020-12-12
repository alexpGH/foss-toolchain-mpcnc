#Basic aerodynamic equations

I collect here some basic equatin wich we need e.g. for airfoil dimensioning.

Total lift force

$$
\begin{equation}
F_{L}=\frac{1}{2}\rho v^2 c_{L} S=m_{plane} \cdot g  \label{eq:liftForce1}
\end{equation}
$$
 
with
<br>$F_{L}$: lift force (N)
<br>$\rho$: denisty of air (we typ. use 1.1673 kg/m³ at 500m)
<br>$v$: velocity (of the plane, m/s) 
<br>$c_{L}$: total lift coefficient
<br>$S$: projected surface (m²)

We use large letters as indices, e.g. $F_{L}$ and $c_{L}$ to indicate total (integrated over the whole wing) values in contrast to *local* values (e.g. given for a wing section).

We regularly need to determine the lowest velocity, a plane can be flown without loosing height. Therefore, we resolve $\eqref{eq:liftForce1}$ for $v$:

$$
\begin{equation}
v=\sqrt{\frac{2\cdot m_{plane}\cdot g}{\rho c_{L} S}}\label{eq:velocityFromMass}
\end{equation}
$$



Reynolds number:

$$
\begin{equation}
Re=\frac{\rho \cdot v \cdot ch}{\mu}=\frac{v\cdot ch}{\nu} \label{eq:reynolds}
\end{equation}
$$

with
<br>$\mu$: dynamic viscosity
<br>$\nu$: kinematic viscosity of air (we typ. use 1.52 E-05 m²/s at 500m)


[//]: # (What the f $\eqref{eq:sample}$ does it work?)
