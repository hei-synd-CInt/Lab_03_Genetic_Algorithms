# Genetic Algorithms

## Missions & Activities:

### Activity
- **Problem**: Use a Genetic Algorithm (GA) to find a quasi-optimal solution for a simple problem (i.e., solve a mastermind game).
- **Tools**: [DEAP](https://deap.readthedocs.io/en/master/) library *or* other libraries (e.g., [PyGAD](https://pygad.readthedocs.io/en/latest/))
- **Consolidation of ML Glossary**:
  - **Steps**: Initialization, selection, crossover, mutation, evaluation.
  - **Terminology**: Gene, individual (or chromosome), population, parents, children, elite, fitness scores.

- **Implementation of GA**:
  - Solve a mastermind game using GA:
    - Check the files: 
      - sentence_mastermind.py (a simple class providing the game logic: selecting hidden sentence, checking the guess, etc.)
      - example_mastermind.py (an example that shows how to call the methods in sentence_mastermind.py)
  - NOTE: you can use a GA library or implement GA yourself from scratch. The first is faster, the second will require some extra work but it will provide a better understanding of the implementation details of selection, crossover, mutation, etc. In any case, you can start from online examples. If you use the Deap library, check this [example](https://deap.readthedocs.io/en/master/examples/ga_onemax.html). If you want to code all by yourself, check this [example](https://machinelearningmastery.com/simple-genetic-algorithm-from-scratch-in-python/).

 ### Implementing GA (provide these answers in the jupyter notebook)
- Explain the main GA steps also in your code: Initialization, selection, crossover, mutation, evaluation (1 slide per step). (Sanity check) Is there any difference compared to what you saw in the slides?
- Discuss which hyper-parameters you tested (e.g., varying number of generations, mutation rate, etc.) and their impact on the results.
- Discuss which other hyper-parameters you did not test (if any), but would you test if you had more time. 
- What if you used Brute Force to solve the problem? How would you do it? What would be the complexity of the Brute Force approach?
- Optional: compare the results of the GA with the Brute Force approach while increasing the size of the hidden sentence.

## Expected Outcomes:
  - A Jupyter notebook for the optimization of a simple problem.
  - In your notebook, systematically use markdown cells to:
    - Explain the goal of your code.
    - Comment on the results.
    - Provide **direct** answer to the questions in the [Implementing GA](#implementing-ga-provide-these-answers-in-the-jupyter-notebook) section.

## Installation
If you have [Poetry](https://github.com/hei-synd-aml/lab-0-TutoPoetry) on your machine, you can install the dependencies by running the following command in the root directory of the project (where the pyproject.toml file is located):
```bash
poetry install
```

If you don't have Poetry installed, you can install the dependencies using pip (as usual, we strongly suggest to create a virtual environment).

