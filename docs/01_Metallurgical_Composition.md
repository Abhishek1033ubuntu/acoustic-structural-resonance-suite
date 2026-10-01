# Metallurgical Composition & Phase Transformation Kinetics

## 1. Alloy Design Philosophy
The bio-mimetic shape memory alloy **$\text{Fe}_{58.5}\text{Mn}_{26}\text{Si}_{6}\text{Cr}_{5}\text{Ni}_{3}\text{C}_{1.5}$** was developed via the `subatomic-materials-suite` ab initio molecular dynamics framework. The material replaces expensive Ni-Ti shape memory alloys with a high-strength, iron-based matrix optimized for passive acoustic-structural damping.

## 2. Chemical Composition & Elemental Roles

| Element | Weight Fraction (wt%) | Atomic Fraction (at%) | Primary Metallurgical Function |
| :--- | :---: | :---: | :--- |
| **Iron (Fe)** | **Base** | **58.5%** | Primary structural lattice matrix (FCC $\gamma$-austenite baseline). |
| **Manganese (Mn)** | 26.0% | 26.0% | Stabilizes $\gamma$-austenite and controls the stacking fault energy (SFE). |
| **Silicon (Si)** | 6.0% | 6.0% | Promotes reversible $\gamma \rightleftharpoons \varepsilon$ transformation; improves yield strength. |
| **Chromium (Cr)** | 5.0% | 5.0% | Provides passivating oxidation resistance in high-temperature flow environments. |
| **Nickel (Ni)** | 3.0% | 3.0% | Narrows the thermal transformation hysteresis loop to $< 3^\circ\text{C}$. |
| **Carbon (C)** | 1.5% | 1.5% | Interstitial strengthening; stabilizes SFE temperature dependency. |

## 3. Martensitic Phase Transformation Kinetics
The alloy relies on a non-diffusional, stress- and temperature-induced phase transformation between two primary crystal structures:

$$\text{Face-Centered Cubic (FCC, } \gamma\text{-austenite)} \quad \underset{\text{Unloading / Unheated}}{\overset{\text{Stress / Temperature}}{\rightleftharpoons}} \quad \text{Hexagonal Close-Packed (HCP, } \varepsilon\text{-martensite)}$$

* **Austenite Phase ($\gamma$):** Soft, highly ductile state at rest ($E \approx 120\text{ GPa}$).
* **Martensite Phase ($\varepsilon$):** Densely packed, high-stiffness state under operational acoustic strain and thermal loads ($E \approx 185\text{ GPa}$).

## 4. Thermomechanical Processing Requirements
To achieve optimal damping loss capacity ($\eta = 0.26$):
1. **Vacuum Induction Melting (VIM):** Homogenize ingot composition under inert argon atmosphere.
2. **Hot Rolling:** 1150°C solution treatment followed by 50% height reduction.
3. **Pre-Straining (Training):** 3% tensile deformation at room temperature to introduce uniform Shockley partial dislocation networks.
4. **Aging:** Annealing at 600°C for 2 hours to fix interstitial carbon atoms along stacking faults.
