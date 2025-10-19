# Project Abstract

The increasing number of refugees due to natural and man-made disasters presents significant challenges, particularly in ensuring the safe and efficient distribution of food in refugee camps. Panic-driven motion during food distribution often leads to overcrowding, collisions, and fatalities.

In this study, we model the food distribution process using a **crowd dynamics framework** to analyze how movement patterns contribute to injuries and deaths. Our simulations show that as food distribution begins, refugees rush toward the food distribution point, leading to high-density congestion and dangerous interactions.

We explore strategies to mitigate these risks by introducing **fixed obstacles near the food distribution point**. The results demonstrate that:

- A **single obstacle** can reduce fatalities by approximately **15%**.  
- An **optimized two-obstacle configuration** achieves up to a **70% reduction** in deaths.

Additionally, we examine the impact of varying **obstacle parameters**—such as size, placement, and gap distance, and discuss their effects on crowd flow. The findings suggest that **strategic obstacle placement** can significantly improve safety, offering a practical and low-cost intervention for refugee camps.

Future work could explore additional measures, such as **increasing the number of food distribution points**, to further enhance efficiency while addressing logistical constraints.

---

# Research Paper

This project is based on our research work that investigates **Crowd dynamics and obstacle-based safety strategies** for food distribution in refugee camps.

You can read the paper here:  
👉 [**A simple model for panic driven motion in a refugee camp∗ (PDF)**](https://github.com/YashJayswal24/crowd_evacuation/blob/main/panic_driven.pdf)

---



# Code Structure
All code files are located in the this directory. Below is an overview of each file and its functionality:

| File | Description |
|------|--------------|
| `running_code.py` | Main script executed in the terminal. Initializes an instance of the `Simulation` class. |
| `Simulation_class.py` | Coordinates the entire simulation and manages saving results. Contains instances of `Integrators`, `Room`, and `diff_equation`. |
| `Integrators.py` | Handles the numerical integration of the simulation. |
| `Room.py` | Defines all room configurations for simulation tests. |
| `diff_equation.py` | Implements the differential equations governing the forces on agents. Used within the `Integrators` class. |
| `steps_function_quit.py` | Responsible for visualizing the simulation and generating related graphs. |

---
