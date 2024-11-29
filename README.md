# STAT-546-EnFK-Simulation
State-space models have been extensively used in various fields such as signal processing, economics, and weather forecasting due to their versatility in handling time series data. Among the techniques developed for filtering and state estimation, the Ensemble Kalman Filter (EnKF) has proven to be effective in addressing the challenges of non-linearity and high dimensional- ity, though it often suffers from issues such as covariance underestimation and filter divergence. Inspired by the Langevinized Ensemble Kalman Filter (LEnKF), this study explores the effects of modifying the Kalman gain compu- tation by replacing the observation noise Rt by 2Rt in the EnKF. Through nu- merical studies on low-dimensional and high-dimensional systems—including the Ornstein-Uhlenbeck model, Van der Pol oscillator, and Lorenz-96 model, we demonstrate that the modified EnKF achieves better uncertainty quan- tification without compromising state estimation accuracy. These findings suggest the potential for further improvements in ensemble-based filtering methods, particularly in high-dimensional and non-linear systems.
