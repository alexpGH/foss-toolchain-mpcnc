#Basic aerodynamic equations

I collect here some basic equatin wich we need e.g. for airfoil dimensioning.

###Total lift force

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

###Stall velocity
We regularly need to determine the lowest velocity, a plane can be flown without loosing height. Therefore, we resolve $\eqref{eq:liftForce1}$ for $v$:

$$
\begin{equation}
v=\sqrt{\frac{2\cdot m_{plane}\cdot g}{\rho c_{L} S}}\label{eq:velocityFromMass}
\end{equation}
$$



###Reynolds number

$$
\begin{equation}
Re=\frac{\rho \cdot v \cdot ch}{\mu}=\frac{v\cdot ch}{\nu} \label{eq:reynolds}
\end{equation}
$$

with
<br>$\mu$: dynamic viscosity
<br>$\nu$: kinematic viscosity of air (we typ. use 1.52 E-05 m²/s at 500m)

###ResqrtCl
Solving $\eqref{eq:reynolds}$ for $v$, insertion in $\eqref{eq:liftForce1}$ and grouping the terms gives:

$$
\begin{equation}
\underbrace{F_{L}=m_{plane\cdot g}}_{const_1} =\underbrace{\frac{1}{2}\rho \frac{\nu^2\cdot S}{ch^2}}_{const!} \cdot  \underbrace{Re^2\cdot C_{L}}_{\Rightarrow const} \label{eq:resqrtcl1}
\end{equation} 
$$

First, we note that, in horicontal flight, the lift force needs to be constant ($const_1$). For higher velocities $v$ we require less $C_l$ and vice versa. All the values aggregated as $const!$ are definitely constant. From this follows that $Re^2\cdot C_{L}$ needs to be constant, too. Hence: 

$$
\begin{equation}
Re\cdot\sqrt{C_{L}}=const \mid_{horicontal\ flight} \label{eq:resqrtcl2}
\end{equation} 
$$

Note: at a given wing section we have local values (small indices)

$$
\begin{equation}
Re\cdot\sqrt{C_{l}}=const \mid_{@wing\ section,\ horicontal\ flight} \label{eq:resqrtcl3}
\end{equation} 
$$


[//]: # (What the f $\eqref{eq:sample}$ does it work?)
