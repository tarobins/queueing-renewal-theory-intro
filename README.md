# Queueing Theory & Stochastic Renewal Processes: Foundations, Congestion Dynamics & CI/CD Fleet Engineering
### *From Little's Law and Erlang Formulas to Heavy-Traffic Limits, Scheduling Disciplines & Distributed Systems Fleet Sizing*

Welcome to **Queueing Theory & Stochastic Renewal Processes: Foundations, Congestion Dynamics & CI/CD Fleet Engineering**! Designed in the pedagogical spirit of Richard McElreath's *Statistical Rethinking*, this course bridges mathematical rigor, physical intuition, and numerical simulation from scratch.

---

## 🚗 Twin Companion Architecture

The curriculum is organized into **two synchronized 1-to-1 parallel tracks**:

* 📖 **[Conceptual Track (`conceptual/`)](conceptual/README.md)**: A deep reading edition focusing on mental models, foundational derivations, physical intuition, and rigorous mathematical arguments (Detailed Balance, The Inspection Paradox, The Variance Penalty, and The Non-Linearity of Congestion).
* 🐍 **[Python Laboratory (`python/`)](python/README.md)**: A hands-on computational lab manual implementing discrete-event queue simulators, stochastic processes, and analytical formulas from scratch using `numpy`, `scipy`, and `matplotlib`.

---

## 📚 Master Curriculum Syllabus & Reference Appendix (`00`–`11`)

| Ch | Conceptual Track | Python Lab | Part | Core Topics & Key Concepts |
| :--- | :--- | :--- | :--- | :--- |
| **00** | **[Ch 00](conceptual/00_START_HERE.ipynb)** | **[Ch 00 (Python)](python/00_START_HERE.ipynb)** | Part I | The Big Picture — Why Average Utilization Lies & The Calculus of Congestion, Traffic Intensity $\rho$, The Flaw of Averages |
| **01** | **[Ch 01](conceptual/01_little_law_and_conservation_of_flow.ipynb)** | **[Ch 01 (Python)](python/01_little_law_and_conservation_of_flow.ipynb)** | Part I | Conservation of Flow — Little's Law ($L = \lambda W$), Operational Envelope & Throughput Bounds, Work-in-Progress (WIP), Subsystem Decomposition |
| **02** | **[Ch 02](conceptual/02_poisson_processes_and_memoryless_arrivals.ipynb)** | **[Ch 02 (Python)](python/02_poisson_processes_and_memoryless_arrivals.ipynb)** | Part I | Random Arrivals — Poisson Processes, Exponential Inter-Arrivals, Merging & Thinning, and PASTA (Poisson Arrivals See Time Averages) |
| **03** | **[Ch 03](conceptual/03_birth_death_chains_and_mm1_mminf.ipynb)** | **[Ch 03 (Python)](python/03_birth_death_chains_and_mm1_mminf.ipynb)** | Part I | Continuous-Time Markov Chains — Birth-Death Detailed Balance, $M/M/1$, $M/M/c$, Erlang-C Waiting Formulas, and Statistical Pooling Gain |
| **04** | **[Ch 04](conceptual/04_the_inspection_paradox_and_renewal_theory.ipynb)** | **[Ch 04 (Python)](python/04_the_inspection_paradox_and_renewal_theory.ipynb)** | Part II | Renewal Theory & The Inspection Paradox — Residual Life, Size-Biased Sampling, Why Random Probes Catch Long Jobs, and Elementary Renewal Theorem |
| **05** | **[Ch 05](conceptual/05_service_variance_and_pollaczek_khinchine.ipynb)** | **[Ch 05 (Python)](python/05_service_variance_and_pollaczek_khinchine.ipynb)** | Part II | The Variance Penalty — $M/G/1$ Queues, Pollaczek-Khinchine Formula, $C_v^2$ Amplification, and How Heavy-Tailed Jobs Stall Linearly Stable Systems |
| **06** | **[Ch 06](conceptual/06_kingman_equation_and_heavy_traffic_regimes.ipynb)** | **[Ch 06 (Python)](python/06_kingman_equation_and_heavy_traffic_regimes.ipynb)** | Part II | Heavy-Traffic Limits — Kingman's $G/G/c$ Approximation, The $\frac{\rho}{1-\rho}$ Congestion Hockey Stick, and Shadow Pricing Capacity |
| **07** | **[Ch 07](conceptual/07_queues_with_breakdowns_and_vacations.ipynb)** | **[Ch 07 (Python)](python/07_queues_with_breakdowns_and_vacations.ipynb)** | Part III | Unreliable Servers — Queues with Server Breakdowns, Repair Times, Setup Vacations, and Effective Capacity Degradation |
| **08** | **[Ch 08](conceptual/08_priority_queues_and_scheduling_disciplines.ipynb)** | **[Ch 08 (Python)](python/08_priority_queues_and_scheduling_disciplines.ipynb)** | Part III | Scheduling & Preemption — FIFO vs. SJF/SRPT, Non-Preemptive $c\mu$-Rule, Head-of-Line Blocking, and Tail Latency Control |
| **09** | **[Ch 09](conceptual/09_jackson_networks_and_bottleneck_routing.ipynb)** | **[Ch 09 (Python)](python/09_jackson_networks_and_bottleneck_routing.ipynb)** | Part III | Networks of Queues — Burke's Theorem, Jackson Open/Closed Networks, Bottleneck Analysis, and Load-Balanced Worker Pools |
| **10** | **[Appendix](conceptual/10_appendix_the_queueing_theory_rosetta_stone.ipynb)** | **[Appendix (Python)](python/10_appendix_the_queueing_theory_rosetta_stone.ipynb)** | Reference | Appendix A — The Queueing & Renewal Theory Rosetta Stone, Kendall's Notation Guide & Diagnostic Playbook |
| **11** | **[Appendix](conceptual/11_appendix_queueing_theory_of_flaky_tests_and_ci.ipynb)** | **[Appendix (Python)](python/11_appendix_queueing_theory_of_flaky_tests_and_ci.ipynb)** | Reference | Appendix B — The Queueing & Renewal Theory of Flaky Tests, Retry Storms & Batch Merge Queues |

---

## 🚀 Getting Started

1. Open your local JupyterLab or notebook interface.
2. Navigate to `conceptual/00_START_HERE.ipynb` to begin reading the foundations.
3. Open `python/00_START_HERE.ipynb` to run the accompanying interactive simulations side-by-side!
