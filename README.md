# CI2025_lab2

# 🗺️ Hybrid Genetic Algorithm (GA) for the Traveling Salesperson Problem (TSP)

This repository contains a Python implementation of a **Hybrid Genetic Algorithm (GA)** designed to find near-optimal solutions for the Traveling Salesperson Problem (TSP). The solution combines the exploratory power of a Genetic Algorithm with the local search refinement of the **2-opt heuristic** for improved performance and solution quality.

## ✨ Features

* **Hybrid Approach:** Utilizes a standard Genetic Algorithm (Selection, Crossover, Mutation) and incorporates the powerful **2-opt Local Search** heuristic to refine the best tours found in each generation (`solve_tsp_ga_hybrid`).
* **Performance:** Leverages **NumPy vectorization** (`calculate_tour_length`, `create_distance_matrix`) for fast distance and tour length calculations.
* **Adaptive Parameters:** The solver dynamically adjusts key GA parameters (**Population Size, Generations, Mutation Rate, 2-opt Frequency**) based on the size of the TSP instance (N_cities) to balance solution quality and runtime efficiency.
* **TSP Operators:** Implements **Tournament Selection**, **Order Crossover (OX)**, and **Swap Mutation** operators suitable for the permutation-based TSP.


<img width="406" height="531" alt="Screenshot 2025-11-06 at 22 27 14" src="https://github.com/user-attachments/assets/5a75b0b4-c66d-4284-8ad8-328abb1b5b97" />


