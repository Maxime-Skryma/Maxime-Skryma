# Maxime Skryma

Hi, I’m Maxime! Currently pursuing a dual degree at ENSAE Paris (Applied Mathematics & Statistics) and HEC Paris (Management & Finance).

I'm passionate about stochastic modeling, machine learning, and (deep) reinforcement learning applied to complex systems. 
I enjoy bridging rigorous mathematical thinking with practical implementation, turning theoretical ideas into robust, scalable solutions that solve real-world problems.
I also enjoy building tools to solve everyday problems, or simply for fun!

I'm always open to new ideas, technical discussions, and opportunities at the intersection of technology, product, and business!

📫 Reach me at **maxime.skryma@gmail.com**  
🔗 Connect on [LinkedIn](https://www.linkedin.com/in/maxime-skryma-08392b282/)

---
Here is a selection of my projects, spanning research internships, personal experimentation, and collaborative work:

### 🧠 Featured Projects & Research


#### 🤖 Atelier Agents — AI Agent Design & Workflow Automation

**Overview:**
Hands-on workshop exploring the design of AI agents and automated workflows. The project investigates how agents can break down tasks, interact with
tools, and coordinate actions to achieve defined objectives.

**Key Components:**
* Agent workflow design and task decomposition
* Tool integration for context-aware actions
* Exploration of agent coordination and automation patterns
* Practical experiments to evaluate agent behavior and limitations

**Technologies & Concepts:** AI Agents · Tool Integration · Workflow Automation · Agent Coordination
🔗 [View Project Repository](https://github.com/Maxime-Skryma/atelier-agents)

---

#### 📈 Hawkes Processes & Deep RL for Crypto Market Making

**Overview:**  
A two-part research project exploring cryptocurrency market making, from spread modelling and market microstructure to Hawkes-based simulation and deep reinforcement learning. The latest study compares TD3 and SAC with Avellaneda–Stoikov on historical DOTUSDT sessions, examining how transaction costs, inventory risk and execution assumptions affect performance.

**Key Components:**
* Multivariate Hawkes calibration and simulation of clustered order-flow arrivals
* Synthetic policy training followed by historical fine-tuning
* TD3 and SAC market-making policies compared with classical controls
* Policy selection on 12 monthly validation sessions in 2024 and evaluation on 22 monthly sessions from January 2025 to October 2026
* Sensitivity analysis across three fee settings and zero-, one- and two-tick execution rules
* Analysis of training variability, regime changes and the limitations of a single pooled Hawkes calibration

**Findings:**  
The learned policies outperform Avellaneda–Stoikov in some fee settings, but all three methods have negative average net P&L under the primary one-tick execution rule. Results remain exploratory, with substantial sensitivity to execution assumptions and no clear evidence of a consistent advantage across the observed sessions.

**Technologies:** Python · PyTorch · NumPy · pandas · SciPy · Numba · Matplotlib · Hawkes Processes · Deep Reinforcement Learning

🔗 [Part 1 — Spread_Crypto: initial spread and market-making study](https://github.com/Maxime-Skryma/Spread_Crypto)  
🔗 [Part 2 — BTC_Hawkes_Deep_RL: Hawkes simulation, TD3/SAC and historical evaluation](https://github.com/Maxime-Skryma/BTC_Hawkes_Deep_RL)

---

#### ⚡ Mean-Field Control & Deep RL

**Overview:**  
Research conducted at the MathFi Lab (CMAP, École Polytechnique) supervised by Pr. Huyên Pham. Formulated and implemented a deep reinforcement learning framework (DDPG, TD3) to approximate large-population decision problems via Mean-Field Control.

**Key Components:**
* Sample-complexity and convergence bounds for continuously-indexed agents
* Continuous action-space deep RL (DDPG, TD3) architecture
* Numerical validation against closed-form Riccati solutions

**Technologies:** Python · TensorFlow · NumPy · SciPy · Stochastic Calculus · Deep RL  
🔒 *Repository currently private (ongoing research paper / publication in progress)*

---

⚙️ More projects on the way. Currently cleaning up, documenting, and pushing completed codebases (simulation engines, research scripts, and trading experiments).
