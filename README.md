# RL-Multi-Armed-Bandits

## Project: Epsilon-Greedy Comparison in a Non-Stationary Environment

This project implements a solution to the classic **10-Armed Testbed Problem** using the **epsilon-greedy ($\epsilon$-greedy)** action-selection strategy ($\epsilon=0.1$). The primary focus is a comparative analysis of two different action-value update methods within a **non-stationary environment** where the true optimal arm drifts over time.

### Key Learning Objectives:

* **Action Selection:** Implementation of $\epsilon$-greedy (Exploration vs. Exploitation).
* **Value Estimation:** Comparison of two core learning methods:
    1.  **Sample-Average Method:** Best for stationary environments.
    2.  **Constant Step-Size ($\alpha=0.1$) Method:** Best for **non-stationary environments** due to its ability to forget older rewards.
* **Non-Stationarity:** The true mean rewards ($\mathbf{q}^*(a)$) are designed to **drift randomly** each time step to challenge the learning algorithm.

### Expected Output:

The resulting plots illustrate the convergence of both methods across 10,000 steps, typically showing the **constant step-size method** achieving a higher percentage of optimal actions in the long run.
