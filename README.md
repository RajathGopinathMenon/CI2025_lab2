# CI2025_lab2

# 🗺️ Hybrid Genetic Algorithm (GA) for the Traveling Salesperson Problem (TSP)

This repository contains a Python implementation of a **Hybrid Genetic Algorithm (GA)** designed to find near-optimal solutions for the Traveling Salesperson Problem (TSP). The solution combines the exploratory power of a Genetic Algorithm with the local search refinement of the **2-opt heuristic** for improved performance and solution quality.

## ✨ Features

* **Hybrid Approach:** Utilizes a standard Genetic Algorithm (Selection, Crossover, Mutation) and incorporates the powerful **2-opt Local Search** heuristic to refine the best tours found in each generation (`solve_tsp_ga_hybrid`).
* **Performance:** Leverages **NumPy vectorization** (`calculate_tour_length`, `create_distance_matrix`) for fast distance and tour length calculations.
* **Adaptive Parameters:** The solver dynamically adjusts key GA parameters (**Population Size, Generations, Mutation Rate, 2-opt Frequency**) based on the size of the TSP instance (N_cities) to balance solution quality and runtime efficiency.
* **TSP Operators:** Implements **Tournament Selection**, **Order Crossover (OX)**, and **Swap Mutation** operators suitable for the permutation-based TSP.


Problem	                   N Cities	Best Score
problem_g_10.npy	              10	1398.03
problem_g_20.npy	              20	1362.06
problem_g_50.npy	              50	2189.28
problem_g_100.npy	             100	2624.30
problem_g_200.npy	             200	4129.90
problem_g_500.npy	             500	5807.69
problem_r1_10.npy	              10	241.31
problem_r1_20.npy	              20	327.43
problem_r1_50.npy	              50	498.67
problem_r1_100.npy	           100	884.35
problem_r1_200.npy	           200	1012.05
problem_r1_500.npy	           500	1838.40
problem_r2_10.npy	              10	339.85
problem_r2_20.npy	              20	411.02
problem_r2_50.npy	              50	631.54
problem_r2_100.npy	           100	855.43
problem_r2_200.npy	           200	1221.97
problem_r2_500.npy	           500	1849.95
problem_g_1000.npy            1000  8838.44      
problem_r1_1000.npy           1000  3141.14      
problem_r2_1000.npy           1000  2618.75      

