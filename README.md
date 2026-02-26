# IMU-Based Gait Phase Estimation for Phase-Varying Modeling

A simple Python project to estimate continuous gait phase (0–100%) from hip flexion angle data using angular velocity integration and phase unwrapping.  
This serves as a foundational step for phase-varying (PV) models in gait analysis, inspired by data-driven approaches to predict kinematic responses in neurological rehabilitation.

## Motivation
Accurate gait phase is essential for phase-varying models that predict gait dynamics after neurological injury or in response to interventions (e.g., exoskeletons).  
This project demonstrates posture-based phase computation from joint angle proxies, aligning with research in gait neuromechanics and rehabilitation.

## Features
- Generates synthetic hip flexion angle data (normal gait cycle)
- Computes angular velocity and cumulative phase
- Normalizes phase to 0–100% of the gait cycle
- Visualizes angle, velocity, and resulting phase

## Requirements
- Python 3.x
- NumPy
- Matplotlib

No external datasets required — fully synthetic.

