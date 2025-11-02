# PhaseTransitionsProject
Critical Slowing Down

## Overview
- Theory: Derive the concept of dynamic critical exponents z and how autocorrelation times diverge near criticality.
- Computation: Simulate the Ising model using local (Metropolis) and cluster (Wolff) updates. Measure autocorrelation times as T→Tc.
- Integration: Compare the scaling of relaxation times for different algorithms, illustrating both universality and algorithmic efficiency.

Extra challenge: Try extracting the dynamic exponent z.

## Summary
**Aim**: Investigate how correlation times diverge near a critical point.

**Tasks**:
1. Implement the 2D Ising model with both Metropolis and Wolff algorithms.
2. Measure autocorrelation functions of magnetization and energy.
3. Extract autocorrelation times near Tc.
4. Compare scaling of relaxation times between algorithms.
    
**Deliverables**:
- Plots of autocorrelation times vs. temperature.
- Estimate of dynamic critical exponent z.
- Comparison of algorithm efficiency at criticality.
    
**Suggested References**:
- Sokal, “Monte Carlo Methods in Statistical Mechanics: Foundations and New Algorithms” (1997).
- Landau & Binder, A Guide to Monte Carlo Simulations in Statistical Physics (2009).
