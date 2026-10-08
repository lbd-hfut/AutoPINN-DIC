# AutoPINN-DIC

**Reinforcement Learning-Guided Adaptive Solver for Physics-Informed Neural Network Digital Image Correlation**

AutoPINN-DIC is a research framework for developing reinforcement learning-driven adaptive optimization strategies for Physics-Informed Neural Network Digital Image Correlation (PINN-DIC).

The project aims to eliminate repetitive, case-specific manual tuning by introducing an RL agent that dynamically controls solver parameters based on optimization progress, image-matching residuals, and convergence diagnostics.

The framework is designed to support:

- **Adaptive Optimization:** Automatic learning-rate scheduling and Adam/L-BFGS switching.
- **Intelligent Convergence Control:** Dynamic optimization budgets and early stopping.
- **Adaptive Sampling:** Future RL-guided selection of informative DIC training points.
- **Generalization:** Reusable solver policies across speckle patterns, deformation fields, noise conditions, and ROI geometries.
- **Accuracy and Efficiency:** Joint evaluation of displacement accuracy, strain accuracy, convergence reliability, and computational cost.

The ultimate goal is to develop a robust, self-adaptive PINN-DIC solver that minimizes manual intervention while maintaining high measurement accuracy.
