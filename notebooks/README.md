Run the simulation in Colab: [open notebook](https://colab.research.google.com/drive/1CBUYUHLn_6CGM7Tzrj_faQXnR3Il297R?usp=sharing)
# QIH Simulator: Quantified Inference of Health

This notebook simulates **QIH**, a thermodynamic signal of adaptive health capacity in complex systems — including humans, ecosystems, or machines.

QIH is defined as:

$$\[
Q_{\text{ih}}(t) = \mathcal{B}(t) \cdot \frac{d^2 \Phi(t)}{dt^2}
\]$$

Where:

- \( \Phi(t) \): Entropy flux — the rate of entropy exported from the system (units: J/K·s)  
- \( \mathcal{B}(t) \): Boundary responsiveness — how well the system preserves structure under stress (unitless)  
- \( \frac{d^2 \Phi(t)}{dt^2} \): Acceleration of entropy export (units: J/K·s³)

---

## Units

**QIH has units of:**  
\[
[J/K \cdot s^3]
\]

This represents **adaptive thermodynamic capacity** — how rapidly and effectively a system can adjust its entropy export in response to demand.  
In plain terms: not just *doing*, but *adapting*.

---

## Simulation Workflow

1. Define time-varying entropy parameters:
   - `dS_internal_dt`: Internal entropy accumulation rate (J/K·s)
   - `phi`: External entropy export rate (J/K·s)
   - `B`: Boundary responsiveness (unitless, between 0 and 1)

2. Compute QIH:
   - Optionally smooth or interpolate noisy signals
   - Output raw and modulated QIH values over time

3. Visualize and interpret:
   - Stability, fragility, recovery, or collapse modes
   - Compare across systems or states

---

## System Examples

Use included or custom entropy profiles to simulate:

- A human recovering from acute stress
- An AI system under thermal or bandwidth load
- A forest regrowing after fire
- Any system that manages internal order and external dissipation

---

## Notes on Interpretation

- Positive QIH values suggest **adaptive readiness** — the ability to ramp up entropy export
- Near-zero values indicate **baseline regulation**
- Large negative values often signal **recovery or deactivation**
- All values are relative to the system's boundary coherence and context

---

## How to Use

1. Open the notebook in [Google Colab](https://colab.research.google.com/)  
2. Modify the entropy inputs and boundary factor  
3. Run the cells to compute and visualize QIH  
4. Use plots and outputs to understand system resilience

---

## License and Attribution

This model is part of the **QIH Project**:  
_Quantified Inference of Health_ — an open framework for simulating adaptive thermodynamic integrity in complex systems.

Developed and maintained by the [Guild Members](https://github.com/projectvitalis) under the Charter of Project VITALIS.
