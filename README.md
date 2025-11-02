This repository contains selected research materials related to **Quantum Computing Applications** (in Spanish).

## 📂 Contents

Notebooks include both **theoretical explanation** and **mathematical and coding implementations** on different problems. 


`Pennylane.ipynb`: Introduction to the **library** and exercises.

`FALQON.ipynb`: **FALQON / FALQON-C** for combinatorial optimization (toy QUBO, knapsack, max-clique).

`QAOA.ipynb` and `QAOA_KNAPSACK_PROBLEM.ipynb`: **QAOA variants** for combinatorial optimization (toy QUBO, number partitioning problem, knapsack).

`VQE.ipynb` and `VQE_JRP.ipynb`: **VQE variants** for combinatorial optimization (toy QUBO, number partitioning problem, knapsack, job reassignment problem).

`Grover.ipynb` and `Grover_Adaptative_Search.ipynb`: **Grover algorithm** and applications, **Grover Adapative Search** for binary optimization.

`Quantum_Annealing.ipynb`: **Quantum Annealing** for optimization (toy QUBO, number partitioning problem, knapsack, TSP, N-queens, job reassignment problem). 


## ⚙️ Requirements

Python 3.11
PennyLane, Qiskit, Matplotlib, ... (see `requirements.yml`)

## 🚀 Setup & Use

Download the repository as a zip file. If used locally instead of Google Colab, unzip it and create an environment using the requirements.yml file. 

`conda env create -f requirements.yml`

`conda activate quantum`

Open any notebook and run cells top-to-bottom. Notebooks are self-contained and use synthetic/example data.

## 📑 Notes

Methods and encodings are based on public literature; original implementations and didactic extensions here are my own.
No proprietary or internal materials are included.


## 🧑‍💻 Author
**Carlos Soria Elizalde**

## 📜 License
**MIT**

## 📞 Contact
[carlosoriaeli@gmail.com]
