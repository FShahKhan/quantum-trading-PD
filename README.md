# Quantum Advantage in Strategic Markets

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/FShahKhan/quantum-trading-PD/blob/main/quantum_market_PD_valid.ipynb)


This notebook simulates the strategic advantage of quantum traders in financial markets, based on the framework from *Khan et al. (2025)*:  
**“Quantum Advantage in Trading: A Game-Theoretic Approach”**

## Overview

Most financial models treat market behavior as classical — even when framed as strategic games. But when the market operates in a Prisoner’s Dilemma regime, quantum strategies can offer two distinct advantages:

- A **decisive edge** for a single quantum trader competing against classical players.
- A **better equilibrium** (Pareto superior) when all players adopt quantum strategies.

This notebook demonstrates both effects using **Qiskit**. It simulates a quantum version of the Prisoner’s Dilemma, following the Eisert-Wilkens-Lewenstein (EWL) protocol. The code assumes a preset regime (e.g., PD) identified from real return data in the companion repo [`market-game-state`](https://github.com/YOUR_USERNAME/market-game-state).

## What It Does

- Encodes the 2-player strategic game in a quantum circuit.
- Allows one player to use quantum strategies (e.g. entanglement, rotation gates), while the other remains classical.
- Computes payoffs based on measurement outcomes.
- Compares classical vs quantum outcomes.

## Requirements

- Python ≥ 3.8  
- [Qiskit](https://qiskit.org/documentation/) (tested with `qiskit` ≥ 1.0)

Install with:

```bash
pip install qiskit
```

## Running the Notebook

Open and run `quantum_market_simulation.ipynb` in [Google Colab](https://colab.research.google.com/), Jupyter, or your preferred environment. The simulation is designed to work **fully on the simulator**, no quantum hardware needed.

## License

This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/).

