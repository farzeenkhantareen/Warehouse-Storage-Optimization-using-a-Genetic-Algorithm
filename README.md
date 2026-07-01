# 📦 Warehouse Storage Optimization using Genetic Algorithm

> A Python implementation of **Warehouse Storage Optimization** using a **Genetic Algorithm (GA)** to intelligently assign products to storage zones while minimizing constraint violations.

---

## 📌 Overview

This project simulates a warehouse management system where products must be assigned to suitable storage zones based on multiple constraints.

The optimization is performed using a **Genetic Algorithm**, which evolves candidate storage plans over multiple generations to find the most efficient and feasible solution.

---

## ✨ Features

* 🧬 Genetic Algorithm optimization
* 📦 Intelligent warehouse zone allocation
* ⚖️ Weight capacity management
* ❄️ Temperature-controlled storage support
* ☣️ Hazardous material handling
* 🥛 Fragile product placement
* 🚚 High-demand product optimization
* 📊 Automatic Excel report generation
* 📋 Constraint violation reporting

---

## 🧠 Optimization Constraints

The algorithm considers several real-world warehouse constraints:

* Zone weight capacities
* Heavy items stored on heavy-duty floors
* Fragile items placed on designated shelves
* Hazardous materials isolated safely
* Temperature-sensitive products stored correctly
* High-demand products placed near dispatch areas
* Food and chemical products kept separate
* Product category grouping

---

## 🧬 Genetic Algorithm Workflow

The optimization process follows these steps:

1. Generate an initial random population.
2. Evaluate each chromosome using a fitness function.
3. Select parents using Tournament Selection.
4. Produce offspring using Single-Point Crossover.
5. Apply Random Mutation.
6. Preserve the best solution through Elitism.
7. Repeat until the maximum generations or an optimal solution is found.

---

## 📊 Fitness Function

The fitness function minimizes penalties caused by:

* Capacity violations
* Incorrect storage locations
* Hazardous safety violations
* Temperature violations
* Fragile item placement errors
* Food and chemical conflicts
* Improper high-demand storage
* Product category separation

A **lower fitness score indicates a better warehouse layout**.

---

## 📁 Project Structure

```text
📦 Warehouse-Storage-Optimization
├── main.py
├── README.md
└── warehouse_plan.xlsx
```

---

## 🛠️ Technologies Used

* Python
* Genetic Algorithm
* OpenPyXL
* Evolutionary Computing
* Object-Oriented Programming

---

## 📈 Output

The program generates:

* 📦 Optimized warehouse storage assignments
* 📊 Zone utilization summary
* ⚠️ Constraint violation report
* 📄 Formatted Excel workbook with multiple sheets

---

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/your-username/Warehouse-Storage-Optimization.git
```

Navigate to the project folder:

```bash
cd Warehouse-Storage-Optimization
```

Install the required dependency:

```bash
pip install openpyxl
```

Run the program:

```bash
python main.py
```

---

## 📚 Concepts Covered

* Genetic Algorithms
* Evolutionary Optimization
* Constraint Satisfaction
* Warehouse Management
* Resource Allocation
* Fitness Evaluation
* Tournament Selection
* Mutation & Crossover
* Elitism

---

## 👨‍💻 Author

**Muhammad Farzeen Khan Tareen**
