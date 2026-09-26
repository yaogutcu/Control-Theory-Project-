# Automatic Control Systems: Analytical Design and Simulation

> This project focuses on the rigorous mathematical modeling, stability analysis, and controller design for complex, real-world dynamic systems. 
> 
> ⚠️ **Disclaimer:** Please note that the exact problem statements, proprietary system parameters, and the complete 20-page handwritten analytical solutions have been intentionally omitted from this public repository for academic confidentiality and intellectual property reasons.

---

## Phase 1: Real-World Problem Formulation & Analytical Solutions

The core of this project revolves around solving advanced control engineering problems derived from practical, real-world physical systems. Instead of relying solely on computational software to generate results, the foundation of this project was built entirely on rigorous, traditional mathematical analysis. 

The theoretical work culminated in a comprehensive **20-page handwritten engineering report**, detailing step-by-step mathematical derivations. This extensive analytical phase covered various fundamental and advanced control theory concepts, including transfer function derivation, system stability assessment, and complex controller tuning. Below are select excerpts showcasing the analytical methodology:

<p align="center">
  <img src="Figures/Figure2_Example%20Hand%20Written%20Routh%20Hurwitz.png" alt="Routh Hurwitz Stability Analysis">
  <br>
  <em><b>Figure 1:</b> Hand-calculated stability assessment of the closed-loop system utilizing the Routh-Hurwitz criterion.</em>
</p>

<p align="center">
  <img src="Figures/Figure3_Hand%20Written%20Root%20Locus.png" alt="Root Locus Sketch">
  <br>
  <em><b>Figure 2:</b> Analytical sketching and pole-zero mapping for the Root Locus trajectory analysis.</em>
</p>

<p align="center">
  <img src="Figures/Figure4_Controller%20Design%20Hand%20Written.png" alt="Controller Design">
  <br>
  <em><b>Figure 3:</b> Detailed mathematical formulation for the required compensator design.</em>
</p>

<p align="center">
  <img src="Figures/Figure1_Example%20Hand%20Written%20PID%20Design.png" alt="PID Design">
  <br>
  <em><b>Figure 4:</b> Analytical parameter calculation for Proportional-Integral-Derivative (PID) controller tuning.</em>
</p>

---

## Phase 2: Software Verification & Simulation

While rigorous mathematical calculations form the foundation of control engineering, verifying these theoretical results in a dynamic environment is crucial to ensure system stability and performance criteria (such as overshoot, settling time, and steady-state error) are met.

To validate the 20 pages of hand-calculated parameters, the theoretical models and the designed controllers were transferred into a digital simulation environment. Using **MATLAB/Simulink**, the systems were modeled dynamically. The simulated step responses perfectly aligned with the analytical predictions, successfully verifying the accuracy of the manual calculations and proving the real-world viability of the designed control systems.

<p align="center">
  <img src="Figures/Figure5_Simulink%20PID%20Test.png" alt="Simulink Verification">
  <br>
  <em><b>Figure 5:</b> Verification of the analytically derived controller parameters in the MATLAB/Simulink dynamic simulation environment.</em>
</p>
