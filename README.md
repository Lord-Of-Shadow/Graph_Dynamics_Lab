# **Graph_Dynamics_Lab**

A collection of three homework projects exploring the fascinating world of **network dynamics**, **statistical learning**, and **graph-based methodologies**. Each project delves into unique problems, from epidemic modeling to network flows and learning dynamics.

---

## **Homework 1: Network Flow Chronicles**
This homework investigates the dynamics of network flow using graph theory and optimization techniques. It focuses on problems such as maximum flow, minimum cut, and matching in bipartite graphs.

### **Key Problems:**
1. **Minimum Cut and Maximum Flow**:
   - Identified edges to remove for preventing flow between specific nodes.
   - Calculated the maximum flow between source and sink nodes using capacity constraints.
2. **Capacity Augmentation**:
   - Studied how additional capacities improve throughput.
   - Analyzed the impact of distributing extra capacities on network efficiency.
3. **Matching in Bipartite Graphs**:
   - Implemented max-flow methods to solve perfect and optimal matchings in bipartite graphs with constraints.

### **Methodology**:
- Utilized **NetworkX** for graph representation and flow algorithms.
- Applied the **max-flow/min-cut theorem** for flow optimization.
- Created and analyzed bipartite graphs for real-world matching problems.

---

## **Homework 2: Dynamic Net Explorer**
This project dives into **continuous-time Markov chains (CTMCs)** and explores their applications in dynamic systems and opinion formation on networks.

### **Key Problems:**
1. **Random Walk Simulations**:
   - Simulated particle movements on a network using transition rate matrices.
   - Calculated average return and hitting times, comparing simulation results with theoretical values.
2. **French-DeGroot Dynamics**:
   - Modeled opinion dynamics on graphs using linear averaging.
   - Explored convergence to consensus states under varying conditions.
3. **Impact of Structural Changes**:
   - Simulated changes in graph structure by removing edges and analyzing the effect on dynamics.

### **Methodology**:
- Used **Poisson processes** for continuous-time simulations.
- Implemented matrix computations for probability transitions and eigenvector-based consensus.
- Visualized dynamics and structural changes with **Python and Matplotlib**.

---

## **Homework 3: Pandemic Graphs**
This homework models real-world problems like the **H1N1 pandemic in Sweden (2009)** and explores epidemic spread on networks using the SIR model and graph coloring for distributed learning.

### **Key Problems:**
1. **Epidemic Simulation**:
   - Simulated disease spread on k-regular and preferential attachment graphs using the SIR model.
   - Compared dynamics with and without vaccination.
2. **Parameter Estimation**:
   - Optimized network and epidemic parameters (k, β, ρ) using stochastic gradient descent to match real-world data.
3. **Graph Coloring**:
   - Solved coloring problems for conflict-free Wi-Fi channel assignments in a distributed setting.

### **Methodology**:
- Modeled epidemic spread using **SIR dynamics** on graphs generated with **preferential attachment models**.
- Utilized **root-mean-square error (RMSE)** to align simulated data with real-world statistics.
- Implemented a distributed learning algorithm to minimize conflicts in graph coloring.

---

## **Methodology Overview**
Across all three projects, the following tools and techniques were used:
- **NetworkX** for graph modeling and analysis.
- **NumPy and SciPy** for numerical computation and matrix manipulation.
- **Matplotlib** for visualization of graphs and dynamic behaviors.
- **Stochastic simulations** and gradient-based parameter optimization.
- Application of **linear algebra**, **probability theory**, and **distributed algorithms**.

---

This repository not only showcases practical applications of network dynamics but also serves as a template for tackling complex, real-world problems using graph-based methods.
