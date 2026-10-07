# Optimization in the Family-Farming Supply Chain (Master's Research)

**A Prize-Collecting TSP variant for milk-collection logistics, solved with GRASP + 2-opt**

🌐 **Language / Idioma:** **English** | [Português](README.pt-BR.md)

---

[![Java](https://img.shields.io/badge/Java-007396.svg?logo=openjdk&logoColor=white)](https://www.java.com/)
[![Metaheuristic](https://img.shields.io/badge/Metaheuristic-GRASP%20%2B%202--opt-orange.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## Overview

This repository holds the implementation developed during my **Master's research in
Computer Science** (UERN/UFERSA, 2018–2020). It models a variant of the
**Prize-Collecting Travelling Salesman Problem (PCTSP)** applied to the **milk-collection
logistics** of small family farmers, and solves it with a **GRASP** metaheuristic refined
by **2-opt** local search.

> Academic research project. Preserved and documented as part of my Operational
> Research portfolio.

## Problem

Milk must be collected from dispersed small producers under cost and capacity
considerations, where visiting each producer yields a "prize" but incurs travel cost.
The objective balances collected prize against routing cost — a Prize-Collecting TSP.

## Method

- **Constructive phase:** greedy randomized construction (GRASP).
- **Local search:** 2-opt improvement of the routes.
- **Experiments:** real and synthetic instances.

## Project structure

```
.
├── src/br/com/uern/projeto/   # Java source
├── bin/                       # Compiled classes
└── doc/                       # Documentation
```

## Build & run

```bash
git clone https://github.com/roberval1994/Masters-Thesis-Milk-Collection-TSP-GRASP.git
cd Masters-Thesis-Milk-Collection-TSP-GRASP

# Compile
javac -d bin src/br/com/uern/projeto/*.java
# Run (adjust the main class name as needed)
java -cp bin br.com.uern.projeto.Main
```

## Tech stack

`Java` · `GRASP` · `2-opt` · `Prize-Collecting TSP`

## Author

**Roberval Gonçalves Moreira Filho** — Data Scientist | Operational Research Analyst
MSc in Computer Science, UERN/UFERSA

[![LinkedIn](https://img.shields.io/badge/LinkedIn-robervalOr-blue)](https://www.linkedin.com/in/robervalOr)
[![GitHub](https://img.shields.io/badge/GitHub-roberval1994-black)](https://github.com/roberval1994)

## License

Released under the MIT License. See [LICENSE](LICENSE).
