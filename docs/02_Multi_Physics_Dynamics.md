# Multi-Physics Dynamics & Acoustic-Structural Coupling

## 1. Acoustic-Structural Lock-In Phenomenon
Acoustic cavity pressure waves ($P_{ac}$) in thin-walled containment ducts drive flexural wall displacement ($w$). When the internal acoustic cavity frequency ($f_{ac}$) coincides with the structural shell natural frequency ($f_{struct}$), energy transfer locks in, amplifying dynamic stress levels up to 73.1 dB (exceeding the 60 dB high-cycle fatigue threshold).

The governing coupled wave equation for the containment shell is:

$$D \nabla^4 w(r, \theta, t) + \rho h \frac{\partial^2 w(r, \theta, t)}{\partial t^2} + c \frac{\partial w(r, \theta, t)}{\partial t} = P_{ac}(r, \theta, t)$$

Where:
* $D = \frac{E(T, P, \sigma) h^3}{12(1-\nu^2)}$ is the flexural rigidity of the shell.
* $E(T, P, \sigma)$ is the state-dependent Young's modulus.
* $\rho h$ is the mass per unit surface area.

## 2. Dynamic Elastic Modulus Shift (Anti-Lock Detuning)
Unlike conventional alloys with fixed elastic moduli, the Fe-SMA metamaterial dynamically alters its modulus $E$ as a function of thermal load ($T$) and acoustic pressure stress ($\sigma$):

$$f_{struct}(T, P) = \frac{\lambda_{mn}^2}{2\pi R^2} \sqrt{\frac{E(T, P, \sigma) \cdot h^2}{12 \rho (1-\nu^2)}}$$

Under ambient operational conditions ($T = 120^\circ\text{C}$, $P = 2.5\text{ bar}$):
1. Stress-induced $\gamma \rightarrow \varepsilon$ domain boundary movement stiffens the lattice.
2. Young's modulus increases from $120\text{ GPa}$ to $185\text{ GPa}$.
3. Structural flexural frequency shifts from $680\text{ Hz}$ to $765\text{ Hz}$.
4. The structural mode detunes away from the fixed $680\text{ Hz}$ acoustic cavity driver, destroying the lock-in condition before resonant energy can accumulate.

## 3. High-Capacitance Energy Dissipation
When operating near coincidence boundaries, mechanical energy is dissipated through interfacial friction of migrating $\gamma/\varepsilon$ phase boundaries:

$$\eta = \frac{\Delta W}{2\pi W_{max}} = 0.26$$

This extraordinary internal loss factor (equivalent to $Q \approx 3.8$) clamps peak dynamic stress to $51.7\text{ dB}$, providing a net **21.4 dB attenuation** across the $200\text{ Hz} - 1.5\text{ kHz}$ operational spectrum.
