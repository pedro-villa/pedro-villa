<div align="center">

# Pedro Villa Navarro

**Dual-degree student in Mathematics & Computer Science**  
*Mathematical Modeling · Machine Learning & Optimization · Systems*

<p align="center">
  <a href="#about">About</a> ·
  <a href="#selected-work">Selected Work</a> ·
  <a href="#repositories">Repositories</a> ·
  <a href="#technical-skills">Skills</a> ·
  <a href="#contact">Contact</a>
</p>

</div>

> [!NOTE]
> **Seeking a Summer 2027 Internship in Norway** (mid-June to August).
> 
> *Jeg forstår norsk på B2-nivå og snakker og skriver på B1-nivå (bestått NORSK2000 ved NTNU).*

---

## About

I am a final-year student pursuing a **Dual Degree in Mathematics and Computer Engineering** at the **Universidad de Murcia**. I did an academic exchange year at **NTNU** in Trondheim, Norway. 

My interests sit at the intersection of formal mathematics—especially topology, geometry, and mathematical modeling—and software engineering. I enjoy working across the stack, from low-level C engines and NumPy-based neural networks to full-stack web architectures and real-time multiplayer games.

## Selected Work

### 🚒 Stochastic Firefighter Problem on Graphs
*Sequential Decision-Making & Optimization · CMM-IMI Modeling Competition (UCM Madrid, Oct 2026)*

- **Exact 2-Stage Formulation:** Derived analytical expectation bounds for multi-hop stochastic spread and linearized the decision objective into an exact Mixed-Integer Linear Program (MILP), solved to certified optimality via HiGHS (`scipy.optimize.milp`).

- **Reinforcement Learning / Rollout Policy:** Engineered a time-indexed multi-stage MILP alongside a nested rollout policy (approximate dynamic programming) with Common Random Numbers (CRN), matching near-optimal containment (13.83 vs. 14.00 saved zones) at a **170× speedup** ($<0.1\text{ s}$ vs. $\sim 17\text{ s}$).

- **Stack:** Python, SciPy (HiGHS), NumPy, NetworkX, Monte Carlo simulation.  

  *(Repository currently private pending jury evaluation; summary report available on request).*

---

### 🕸️ Topological Foundations for Ontology Representation
*Knowledge Representation & Topological Data Analysis · B.Sc. Thesis in Computer Science (In progress)*

- Models semantic *is-a* subsumption hierarchies and knowledge graphs as finite posets $(P, \le)$ equipped with the Alexandrov topology.

- Computes topological invariants of structured data via the simplicial order complex $\Delta(P)$: connected components, simplicial homology groups, and Euler characteristic $\chi(\Delta(P))$.

- **Stack:** Python, GUDHI, NetworkX, NumPy (evaluated on WordNet and Gene Ontology).

---

### 📐 Stokes' Theorem on $C^1$ Manifolds via Hausdorff Measures
*B.Sc. Thesis in Mathematics (In progress) · Advisor: Prof. Víctor Jiménez López*

- Rigorous formulation of differential form integration on $C^1$ submanifolds with boundary against Hausdorff measures.

- Circumvents standard $C^2$ chart assumptions by using adapted ambient coordinate projections in general position.

---

### ⚙️ [MiniC to MIPS32 Native Compiler](https://github.com/pedro-villa/minic-compiler)
*Coursework project: Compilers (UMU)*

- End-to-end compiler translating MiniC code into MIPS32 assembly for the MARS simulator.

- Implemented lexical analysis and LALR(1) parsing using Flex and Bison.

- Built intermediate representations of pointer-linked quadruples, compile-time constant folding, and bitmap register allocation (`$t0`–`$t9`).  


---

## Repositories

| Repository | System & Focus Highlights | Stack |
|---|---|---|
| [**nanofiles-p2p**](https://github.com/pedro-villa/nanofiles-p2p) | Hybrid peer-to-peer file sharing system combining a centralized UDP directory service with multithreaded TCP peer transfers. | Java, UDP, TCP, Stop-and-Wait ARQ |
| [**minic-compiler**](https://github.com/pedro-villa/minic-compiler) | End-to-end MiniC compiler with LALR(1) parsing, compile-time constant folding, and bitmap register allocation for MIPS32. | C, Flex, Bison, MIPS |
| [**HandwrittenDigitRecognition**](https://github.com/pedro-villa/HandwrittenDigitRecognition) | Multilayer perceptron and matrix backpropagation written from scratch without autograd libraries, with interactive drawing canvas. | Python, NumPy |
| [**TDT4240-game**](https://github.com/pedro-villa/TDT4240-game) | Real-time multiplayer 2D game (*Loot'em Shoot'em*). Authoritative headless server running a 20 Hz tick loop with multi-client WebSocket synchronization. | Java, LibGDX, WebSockets |
| [**aed2-algorithms-cpp**](https://github.com/pedro-villa/aed2-algorithms-cpp) | Divide-and-conquer, greedy scheduling, and branch-and-bound with cache-conscious memory layouts and POSIX hardware counter benchmarking. | C++17, POSIX |
| [**aed1-data-structures-cpp**](https://github.com/pedro-villa/aed1-data-structures-cpp) | Compact left-child right-sibling tries, separate-chaining hash tables with UTF-8 normalization, and formal BST/AVL rotations. | C++17 |
| [**Lights**](https://github.com/pedro-villa/Lights) | 2D visibility engine featuring custom 2D raycasting, dynamic lighting fields, and line-of-sight stealth AI. | C99, SDL2 |
| [**topologia-de-superficies**](https://github.com/pedro-villa/topologia-de-superficies) | Open lecture notes and proofs on topological classification of compact surfaces, fundamental groups, and CW complexes. | LaTeX, GitHub Actions |
| [**AI_Notebook**](https://github.com/pedro-villa/AI_Notebook) | Web application for logging, auditing, and annotating AI-assisted workflows across coursework. | React, Node.js, Express, MongoDB |

---

## Technical Skills

- **Languages:** Python (primary), C++ (C++17), C99, Java, SQL, Bash, MATLAB, R

- **AI & Scientific Computing:** PyTorch, Scikit-Learn, NumPy, SciPy (HiGHS MILP), NetworkX, Pandas, GUDHI, Matplotlib

- **Systems & Engineering:** Linux/UNIX, Git/GitHub, Docker, WebSockets, POSIX APIs, CMake, \LaTeX

- **Core Methods:** Machine Learning & Statistical Inference, Approximate Dynamic Programming / Rollout Policies (RL), Mixed-Integer Linear Programming (MILP), Graph Algorithms, Cache-Conscious Systems

---

## Contact

- **Email:** [pedrovilla.work@gmail.com](mailto:pedrovilla.work@gmail.com)
- **LinkedIn:** [pedro-villa-navarro](https://www.linkedin.com/in/pedro-villa-navarro)

<p align="center">
  <sub>Murcia, Spain · Available from June 2027</sub>
</p>
