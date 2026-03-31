# Colorization Robustness Study: Baseline Implementation

## Project Overview
This repository contains the initial baseline for research into how color distribution impacts model robustness. 

## Current Limitations (Identified for Refactor)
During the initial phase, I identified the following issues that led to a drop in accuracy:
* **Dataset Scale:** Images were too low-resolution for effective feature extraction.
* **Training Pipeline:** Improper hyperparameter tuning led to suboptimal convergence.

## GSoC 2026 Context
I am currently refactoring this codebase to implement a more robust training pipeline. This work serves as a proof-of-concept for my ability to identify and resolve accuracy bottlenecks—a skill.