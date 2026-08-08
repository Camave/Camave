# Camille Monnier

Computer Engineering student at **Polytechnique Montréal**, working on quantum compilation and industrial data systems.

I'm interested in the layer where software meets hardware constraints — compilers, low-level performance, and systems that have to work under real physical limits. I build things from first principles when I can: a transformer derived from the architecture rather than assembled from a library, an embedded system programmed at register level.

---

## Currently

**Quantum Computing Research Intern — Calcul Québec** *(June 2026 – present)*
Optimizing the circuit transpilation stack for the MonarQ superconducting processor. Implemented SABRE qubit routing and custom optimization passes in the `pennylane-calculquebec` plugin, cutting circuit depth and CZ gate count by 40% and compilation time by 26× against the MQT baseline. Currently designing a QAOA-based layout pass for virtual-to-physical qubit mapping.

**Data Engineering & Application Development Intern — VINCI Construction** *(May 2026 – present)*
Designed and shipped the data platform unifying 24 asphalt plants across Canada — schema design, site interconnection, and Python/SQL ETL pipelines. Real-time monitoring dashboards now used daily by 30+ engineers and technicians. Awarded Best Innovation, VINCI Construction Amérique-Océanie.

---

## Selected work
**[Deep Learning from Scratch](https://github.com/Camave/deeplearning)** — Python, PyTorch, NumPy

Nine steps from a three-parameter neuron to a 47M-parameter language model, each
one measured rather than assumed. Backpropagation derived analytically in NumPy and
verified against numerical gradients; a weight-initialization bug caught this way took a
multi-class classifier from 7.8% to 91.9% test accuracy.

The two trained transformers: **MiniGPT** (2.1M params, 4 blocks, 8 heads, d=256) reaches
1.09 held-out validation loss on character-level Shakespeare — 2.97 perplexity per character.
**Camille0** (47M params, 6 blocks, 6 heads, d=384, GPT-2 BPE) is pretrained on
SlimPajama-6B. Attention, causal masking, and pre-norm residual blocks written from
the architecture, not assembled from library modules.

**[Autonomous Robot — Embedded Systems](https://github.com/Camave/Autonomous-robot)** — C, avr-libc, ATmega324PA
Bare-metal register-level programming on an ATmega324PA in a team of four: interrupt-driven UART/RS-232, I²C peripheral addressing, PWM motor control, and ADC sensor acquisition. Code quality enforced through peer inspections, unit tests, and Git-based configuration management. *(Coursework — repository available on request.)*

---

## Tools

**Languages** — Python, C, C++, SQL, TypeScript
**Quantum** — Qiskit, PennyLane, circuit transpilation, SABRE routing, VQE/QAOA
**Data & ML** — pandas, NumPy, PyTorch, Matplotlib, Grafana, ETL pipeline design
**Systems** — Docker, Git, Linux, bare-metal AVR

---

## Contact

[LinkedIn](https://www.linkedin.com/in/camille-monnier-40a69528b) · [monnier.camille06@gmail.com](mailto:monnier.camille06@gmail.com)

Open to **Summer 2027 internships** in software engineering, quantum computing, and machine learning.
