# Knapsack Optimization: Exact Method vs. Genetic Algorithm

## Project Overview
This project compares the performance of Exact Optimization and Genetic Algorithms (GA) for solving the 0–1 Knapsack Problem using MATLAB.

The study evaluates solution accuracy, convergence behavior, computational efficiency, and scalability.

## Objectives
- Formulate the 0–1 Knapsack Problem mathematically.
- Implement exact and genetic algorithm approaches.
- Compare solution quality and computational performance.
- Evaluate algorithm scalability across different problem sizes.

## Tools and Technologies
- MATLAB
- Integer Programming
- Genetic Algorithms
- Mathematical Optimization
- Data Visualization

## Methodology
1. Mathematical formulation of the 0–1 Knapsack Problem
2. Implementation of exact optimization
3. Implementation of a Genetic Algorithm
4. Convergence analysis for a 20-item instance
5. Scalability testing for 10, 50, 100, 150, and 200 items
6. Comparison of computational time and solution quality

## Key Results

### Convergence Analysis — 20 Items

| Method | Solution Value | Optimality |
|---|---:|---:|
| Exact Method | 541 | 100% |
| Genetic Algorithm | 521 | 96.30% |

### Scalability Analysis

| Items | Exact Value | GA Value | GA Accuracy |
|---|---:|---:|---:|
| 10 | 231 | 231 | 100% |
| 50 | 1570 | 1430 | 91.08% |
| 100 | 2999 | 0 | 0% |
| 150 | 4616 | 0 | 0% |
| 200 | 6596 | 0 | 0% |

## Conclusion
The exact optimization approach achieved optimal solutions with lower computational time across the tested instances.

The Genetic Algorithm demonstrated competitive performance for smaller problems but required improvements in constraint handling and parameter tuning for larger instances.

## Academic Information
**Course:** Operational Research III (MFM3142)

**Institution:** Department of Mathematics, University of Ruhuna, Sri Lanka

**Supervisor:** Dr. D.M. Samaratunga

## Project Files
The repository contains the case study report and, where available, MATLAB implementations and result visualizations.
