# Genetic Algorithm Implementation

This repository contains a Python implementation of a genetic algorithm.

## Overview

Genetic algorithms are a class of optimization algorithms inspired by the principles of natural selection and genetics. They are used to find solutions to optimization and search problems by mimicking the process of natural evolution.

This implementation provides functionalities for:

- Generating chromosomes with random values
- Calculating fitness based on a user-defined mathematical expression
- Regenerating non-fittest chromosomes through mutation or crossover
- Stopping criteria based on the goal, acceptable range, or fixed iterations

## Files

- `genetic_algorithm.ipynb` and `genetic_algorithm.py`: Python script containing the implementation of the genetic algorithm.
- `README.md`: This file, providing an overview and instructions.

## Usage

To use the genetic algorithm implementation:

1. Clone the repository:

   ```git clone https://github.com/anumsaeed0/genetic-algorithm.git```
   
2. Run the genetic_algorithm.py script:

   ```python genetic_algorithm.py```

   Follow prompts to input parameters like chromosomes, variables, goal, iterations, and mathematical expression.

3. Requirements
   - Python 3.x
   - Random library

4. Example Expression
   - Fitness calculation uses expressions like: ```-3*((x)**3)) + 7*((y)**2) + 15```
   - Where x and y are user-defined variables.

## License
This project is licensed under the MIT License.
