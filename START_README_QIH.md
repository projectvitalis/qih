
# Project VITALIS

**A thermodynamic framework for understanding system health**

tl;dr
## Frequently Asked Questions (FAQ)

### 1. What is QIH?

**QIH** (Quantified Inference of Health) is a thermodynamically grounded signal that measures a system’s **adaptive capacity to export entropy**. It captures how effectively a system maintains internal order by offloading entropy to the environment—especially under stress or change.

---

### 2. Why use entropy flux instead of biological or behavioural proxies?

Entropy export is a **universal, measurable quantity**. Unlike proxies (e.g. heart rate variability or cortisol), it applies across systems—humans, ecosystems, machines, markets—because it reflects the core thermodynamic behaviour of adaptation and breakdown.

---

### 3. How is this different from homeostasis or allostasis?

- **Homeostasis** = static balance  
- **Allostasis** = active regulation through change  
- **QIH** = _acceleration_ of entropy export under load  

QIH measures **how responsively a system adapts**, not just whether it's in balance.

---

### 4. What does a high or low QIH value mean?

- **High QIH** → Rapid increase in entropy export  
  (System is adapting, shedding load, or recovering)

- **Low or negative QIH** → Loss of regulatory momentum  
  (System is stiffening, depleting, or collapsing)

QIH is not a measure of activity.  
It is a measure of **thermodynamic responsiveness**.

---

### 5. How do I calculate QIH?

To estimate QIH, define the following:

| Variable             | Description                                | Units         |
|----------------------|--------------------------------------------|---------------|
| `dS_internal/dt`     | Rate of internal entropy generation         | J/K·s         |
| `Φ(t)` (phi)         | Rate of entropy export to the environment   | J/K·s         |
| `B(t)`               | Boundary responsiveness factor              | Unitless      |

Then compute:

```
QIH(t) = B(t) × d²Φ(t)/dt²
```

- `Φ(t)` must be twice-differentiable over time  
- `B(t)` modulates sensitivity based on system boundaries

Final units: **Joules per Kelvin per second squared (J/K·s²)**

---

### 6. What kinds of systems can use QIH?

Any system that:

- Generates internal entropy (e.g. metabolic heat, processing load, disorder)  
- Exports entropy to its environment (e.g. cooling, excretion, data logging)  
- Has a semi-permeable boundary (e.g. skin, network edges, regulatory structures)

QIH applies to:

- 🧠 Humans and sleep states  
- 🌲 Ecosystems and biodiversity collapse  
- 🤖 AI agents and compute degradation  
- 💹 Markets and volatility response  
- 🏥 Clinical health monitoring

---

Want examples? Run the [QIH Simulator](https://colab.research.google.com/github/projectvitalis/qih/blob/main/qih_simulator.ipynb) in Colab or explore [example profiles](https://github.com/projectvitalis/qih/tree/main/examples) like sleep, forest fire, and AI overload.

---

## Welcome

Project VITALIS is an open, evolving framework that defines **health** in thermodynamic terms. It introduces a simple, quantitative model that applies to systems ranging from individual organisms to markets and ecosystems.

This repository hosts the core papers, simulation tools, and supporting materials. It is designed to be accessible to both scientists and curious generalists.

If you’re new to thermodynamics or complex systems, don’t worry because this work is designed to be explored one piece at a time. Start with the definitions or an example that interests you.

---

## Why This Work Matters

Most models of health focus on static traits, risk factors, or outcomes. This project takes a different approach: it proposes that health is a **capacity** measure for a system’s ability to manage entropy adaptively over time.

Entropy, in this context, refers to the degree of disorder or uncertainty in a system. Systems that can export entropy efficiently tend to survive and adapt; those that cannot tend to collapse.

This approach:

- Grounds health in physical principles  
- Enables simulation, modelling, and early warning detection  
- Allows cross-domain comparisons between humans, ecosystems, AI, and institutions  
- Provides new language for collapse, recovery, and resilience  

---

## Core Concept: QIH

The central quantity in this work is **QIH (Quantified Inference of Health)** which is a thermodynamic measure of a system’s adaptive capacity.

It is defined as:

$$
Q_{\text{ih}}(t) = B(t) \cdot \frac{d^2 \Phi(t)}{dt^2}
$$

Where:  
$$\( \Phi(t) \)$$
is the system’s entropy flux (J/K·s)  

$$\( B(t) \)$$ 
is the boundary responsiveness factor (dimensionless)  

$$\( \frac{d^2 \Phi(t)}{dt^2} \)$$ 
is the system’s acceleration in entropy export (J/K·s³)  

**Units**: QIH is measured in joules per kelvin per second squared (J/K·s²).  
This reflects how quickly and effectively a system accelerates its ability to reduce internal disorder.  
High QIH = high adaptive health.

---

## Example Applications

QIH allows us to understand how seemingly very different systems such as sleep, markets, and rainforests maintain their integrity in the face of constant stress. These systems are not just vulnerable to collapse; they are also capable of remarkable adaptation and recovery. QIH captures both possibilities through the same thermodynamic lens.

### Sleep as Adaptive Maintenance  
Sleep is not passive. It is a phase of intense entropy regulation: the brain clears waste, rebalances signalling thresholds, and consolidates information. When QIH is high, sleep cycles are efficient, restorative, and aligned with environmental rhythms. Low QIH may manifest as fragmented sleep, chronic fatigue, or inflammatory overload. Improving QIH through sleep hygiene or circadian alignment supports long-term system survival and performance.

### Markets as Adaptive Information Engines  
Healthy financial markets process uncertainty and reallocate resources dynamically. High-QIH markets show flexible boundary responses (e.g. policy tools, sentiment feedback) and accelerating entropy export through liquidity and innovation. This keeps disorder in check. In contrast, rigid or over-leveraged markets may show declining QIH—an early signal of systemic fragility. QIH allows us to model both resilience and instability in economic systems.

### Rainforests as Self-Stabilizing Networks  
Tropical rainforests manage vast energy and water flows through dense biological feedback. A high-QIH rainforest shows strong boundary responsiveness (e.g. evapotranspiration, pollinator webs) and rising entropy throughput. This supports biodiversity and climate stability. When pressures like deforestation reduce QIH, the system becomes less responsive—eventually tipping into a drier, degraded state. But interventions that strengthen boundary feedbacks can raise QIH and restore stability.

### AI Systems  
In artificial intelligence, QIH may reflect a model’s ability to maintain boundary coherence and adapt to shifting inputs. A high QIH might suggest robust learning and entropy management at the edge of computational saturation. A system with rigid, fixed outputs may exhibit QIH collapse before failure.

---

These examples show how QIH models not only collapse, but also how they flourish. It reveals the physical logic behind resilience: the ability of a system to respond, adapt, and reorganize in ways that preserve or enhance function over time.

---

## How the Work is Structured

### Guild Papers
Each paper applies the QIH framework to a different domain. All are written in clear, accessible language with rigorous mathematical foundations.

- **Paper 01** – *Sleep as Entropy Export Mechanism*: A model for understanding sleep through QIH  
- **Paper 02** – *Ecosystem Collapse at the Entropic Threshold*: Models Amazon rainforest resilience  
- **Paper 03** – *Entropy Without Organs*: Applies QIH to artificial intelligence systems  
- **Paper 04** – *Markets at the Edge*: Uses QIH to model financial system collapse and resilience  

### Simulator
An interactive Colab notebook lets you test and visualize the model. You can plug in your own assumptions and observe how entropy dynamics affect system health.

The simulator is a conceptual tool, not a forecasting engine. It helps you explore how a system *might behave* under different entropy conditions and does not predict what *will happen* in reality.

Try the simulator here: https://colab.research.google.com/drive/17UigtKYuN057WCU6Ccf5dTo4GZdKIqH_?usp=sharing

---

## How to Use This Repository

1. Start with the README (you’re here).  
2. Choose a paper that aligns with your interest area.  
3. Open the simulator to experiment with QIH under different conditions.  
4. Explore the definitions to understand the model in full detail.  

This project is modular. You can engage with it as a scientific framework, a conceptual model, or an exploratory tool. However you decide to engage with it is up to you, and we ask that you let us know what you learn along the way. We are listening.

---

## Who This Is For

- Researchers in health, ecology, economics, or AI  
- Systems thinkers and resilience strategists  
- Policymakers and practitioners working on adaptation and recovery  
- Curious minds interested in foundational dynamics of well-being  

---

## Citation and Licensing

This work is published under an open licence. All material is free to use, adapt, and build upon with attribution. See the LICENSE file for details.

---

## Contact and Collaboration

This work is authored collectively by the **Guild**, under the charter of Project VITALIS. To learn more, contribute, or request collaboration:

projectvitalis@proton.me  
[Website coming soon]  

---

“We cannot restore a system we do not understand. This is our attempt to understand—thermodynamically, mathematically, and ethically—what it means for a system to remain well in a chaotic world.”
