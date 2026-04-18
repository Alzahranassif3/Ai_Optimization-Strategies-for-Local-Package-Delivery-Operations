## Delivery Optimization Project

### Description

This project focuses on optimizing package delivery routes using two metaheuristic algorithms: Simulated Annealing and Genetic Algorithm.
The goal is to minimize total travel distance while prioritizing high-priority deliveries and respecting vehicle capacity constraints.

### Features

* Simulated Annealing optimization
* Genetic Algorithm optimization
* Vehicle capacity constraints handling
* Priority-based delivery optimization
* Route visualization using Matplotlib

### Technologies

* Python
* Matplotlib

### Input

The program reads data from an `input.txt` file:

* Vehicles with capacities
* Packages with coordinates, weight, and priority

### How to Run

1. Prepare `input.txt` file
2. Run the program:

```bash
python app.py
```

3. Choose algorithm:

* 1 → Simulated Annealing
* 2 → Genetic Algorithm

### Output

* Optimized package assignment to vehicles
* Total distance
* Visualized delivery routes

### Algorithms Used

* Simulated Annealing (SA)
* Genetic Algorithm (GA)

### Notes

* The objective function minimizes:
  **Total Distance − Priority Reward**
* High-priority packages are delivered earlier for better scores

