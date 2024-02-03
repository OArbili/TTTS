# TTTS: Tree Test Time Simulation

TTTS (Tree Test Time Simulation) is an innovative implementation aimed at enhancing the robustness of decision trees against adversarial examples, based on the groundbreaking research presented in the paper "TTTS: Tree Test Time Simulation for Enhancing Decision Tree Robustness Against Adversarial Examples". This project encapsulates the practical application of the research, providing a robust, adaptable solution for improving decision tree models against adversarial attacks.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Experiments](#experiments)
- [Citation](#citation)
- [License](#license)
- [Contact](#contact)

## Introduction

Decision trees, while widely used for tabular data learning tasks, are vulnerable to adversarial attacks. TTTS introduces a novel inference-time methodology that integrates Monte Carlo simulations into decision trees, thereby significantly enhancing their robustness. This probabilistic approach to decision paths maintains the core structure of the tree while improving model performance and resilience to various adversarial attacks.

## Features

- **Robust Simulation**: Incorporates Monte Carlo methods into decision trees, introducing a probabilistic modification to decision paths without altering the tree structure.
- **Enhanced Performance**: Empirical analysis on 50 datasets shows improved model performance and robustness against white-box and black-box attacks.
- **Customizable Probability Types**: Supports various probability types to influence path selection during the prediction phase, enhancing decision-making under uncertainty.
- **Extensive Dataset Collection**: Comes with 50 datasets used for comprehensive empirical analysis and experimentation.
- **Comprehensive Documentation**: Includes detailed documentation, usage examples, and results of experiments.

## Installation

TTTS can be easily installed using pip:
```bash
pip install TTTS
```

## Project Structure

The TTTS project is organized as follows to ensure ease of use, reproducibility of results, and a clear understanding of the project's components:

- `code/`: Contains the implementation of the TTTS algorithm.
  - `TTTSClassifier.py`: The main class implementing the TTTS methodology. This classifier introduces a probabilistic approach to decision-making in decision trees, using Monte Carlo simulations.
- `data/`: Includes the 50 datasets used for experiments. These datasets are utilized to demonstrate the effectiveness and robustness of the TTTS methodology against adversarial attacks.
- `experiments/`: Contains scripts and notebooks for running the experiments outlined in the paper. This folder allows users to reproduce the results and to understand the impact of TTTS on model performance and robustness.
- `paper/`: Includes a PDF file of the original research article. This provides users with direct access to the theoretical background, empirical analysis, and insights derived from the research.'


## Usage

After installing TTTS, you can seamlessly integrate it into your machine learning pipeline. The TTTS classifier enhances traditional decision tree classifiers by introducing robustness against adversarial attacks. Follow these steps to use it in your project:

1. **Importing the Classifier**:
   Import the TTTS classifier from the package into your Python script.

  
## Experiments
Navigate to the experiments/ folder to view or run the experiments conducted as part of the research. This section includes scripts for reproducing the results presented in the paper, as well as detailed analysis of the TTTS performance under various conditions.

@inproceedings{ttts2024,
  title={TTTS: Tree Test Time Simulation for Enhancing Decision Tree Robustness Against Adversarial Examples},
  author={Cohen Seffi , Arbili Ofir , Mirsky Yisroel , Rokach Lior},
  booktitle={Proceedings of the AAAI Conference},
  year={2024}
}

This project is licensed under the MIT License. See the LICENSE file for more details.
