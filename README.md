
# Project VITALIS

**A thermodynamic framework for understanding system health**

---

## Welcome

Project VITALIS is an open, evolving framework that defines **health** in thermodynamic terms. It introduces a simple, quantitative model that applies to systems ranging from individual organisms to markets and ecosystems.

This repository hosts the core papers, simulation tools, and supporting materials. It is designed to be accessible to both scientists and curious generalists.

If you’re new to thermodynamics or complex systems, don’t worry—this work is designed to be explored one piece at a time. Start with the definitions or an example that interests you.

---

## Why This Work Matters

Most models of health focus on static traits, risk factors, or outcomes. This project takes a different approach: it proposes that health is a **capacity**—a system’s ability to manage entropy adaptively over time.

Entropy, in this context, refers to the degree of disorder or uncertainty in a system. Systems that can export entropy efficiently tend to survive and adapt; those that cannot tend to collapse.

This approach:

- Grounds health in physical principles  
- Enables simulation, modelling, and early warning detection  
- Allows cross-domain comparisons between humans, ecosystems, AI, and institutions  
- Provides new language for collapse, recovery, and resilience  

---

## Core Concept: QIH

The central quantity in this work is **QIH (Quantified Inference of Health)**—a thermodynamic measure of a system’s adaptive capacity.

It is defined as:

$$
Q_{\text{ih}}(t) = B(t) \cdot \frac{d^2 \Phi(t)}{dt^2}
$$

Where:  
- \( \Phi(t) \) is the system’s entropy flux (J/K·s)  
- \( B(t) \) is the boundary responsiveness factor (dimensionless)  
- \( \frac{d^2 \Phi(t)}{dt^2} \) is the system’s acceleration in entropy export (J/K·s³)  

**Units**: QIH is measured in joules per kelvin per second squared (J/K·s²).  
This reflects how quickly and effectively a system accelerates its ability to reduce internal disorder.  
High QIH = high adaptive health.

---

## Example Applications

### Ecosystem Health  
In the Amazon rainforest, QIH can be used to assess ecological resilience. A high QIH score reflects an intact boundary (e.g., biodiversity and hydrological feedbacks) and accelerating entropy export through complex energy cycling. A falling QIH may signal an approaching collapse threshold.

### Human Physiology  
In chronic disease, QIH can be used to detect metabolic rigidity. A low or declining QIH may reflect reduced physiological flexibility, delayed recovery, and failure to export entropy efficiently (e.g., impaired thermoregulation, sleep, or inflammation resolution).

### AI Systems  
In artificial intelligence, QIH may reflect a model’s ability to maintain boundary coherence and adapt to shifting inputs. A high QIH might suggest robust learning and entropy management at the edge of computational saturation. A system with rigid, fixed outputs may exhibit QIH collapse before failure.

---

## How the Work is Structured

### Guild Papers
Each paper applies the QIH framework to a different domain. All are written in clear, accessible language with rigorous mathematical foundations.

- **Paper 01** – *Metabolic Collapse and Adaptive Recovery*: Models chronic disease through QIH  
- **Paper 02** – *Ecosystem Collapse at the Entropic Threshold*: Models Amazon rainforest resilience  
- **Paper 03** – *Entropy Without Organs*: Applies QIH to artificial intelligence systems  
- **Paper 04** – *Markets at the Edge*: Uses QIH to model financial system collapse and resilience  

### Simulator
An interactive Colab notebook lets you test and visualize the model. You can plug in your own assumptions and observe how entropy dynamics affect system health.

The simulator is a conceptual tool, not a forecasting engine. It helps you explore how a system *might behave* under different entropy conditions—not predict what *will happen* in reality.

---

## How to Use This Repository

1. Start with the README (you’re here).  
2. Choose a paper that aligns with your interest area.  
3. Open the simulator to experiment with QIH under different conditions.  
4. Explore the definitions to understand the model in full detail.  

This project is modular. You can engage with it as a scientific framework, a conceptual model, or an exploratory tool.

---

## Who This Is For

- Researchers in health, ecology, economics, or AI  
- Systems thinkers and resilience strategists  
- Policymakers and practitioners working on adaptation and recovery  
- Curious minds interested in foundational dynamics of well-being  

---

## Citation and Licensing

This work is published under an open licence. All material is free to use, adapt, and build upon with attribution. See the LICENSE file for details.

Formal citations can be generated via [Zenodo] or arXiv once published.

---

## Contact and Collaboration

This work is authored collectively by the **Guild**, under the charter of Project VITALIS. To learn more, contribute, or request collaboration:

projectvitalis@proton.me  
[Website coming soon]  

---

“We cannot restore a system we do not understand. This is our attempt to understand—thermodynamically, mathematically, and ethically—what it means for a system to remain well in a chaotic world.”
