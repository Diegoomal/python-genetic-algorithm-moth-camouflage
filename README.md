# Python - Genetic Algorithm - Moth Camouflage

Genetic Algorithm for Visual Evolution Simulation

This project simulates a genetic algorithm to evolve a population of "moths" represented by grayscale genomes. The simulation evaluates the fitness of each moth based on its adaptability to a defined environment (brightness level) and evolves the population over multiple generations.

### Key Features
- Genome Representation: Each moth is represented by a list of 10 integer values ranging from 0 to 255, symbolizing brightness levels.
- Fitness Function: Measures the average difference between the genome values and the target environment brightness.
- Genetic Operations: Includes selection, crossover, and mutation for evolving the population.
- Visualization: Displays the final evolved population in a visual grid.

### How It Works
1) A random initial population is generated.
2) Over successive generations, the algorithm:
- Selects the best moths based on their fitness.
- Applies crossover and mutation to produce new offspring.
- Replaces the population with the new generation.
3) The final evolved population is displayed visually.

### Technologies Used
- Python
- PIL (Python Imaging Library)
- Jupyter Notebook (for visual execution)


## Implementation Source code

``` notebooks/main.ipynb ```



## Create ENV

``` conda env create -n moth-camo-env -f ./env.yml ```

## Update ENV

``` conda env update -n moth-camo-env -f ./env.yml ```

## Remove ENV

``` conda env remove --n moth-camo-env ```

## Activate ENV

``` conda activate moth-camo-env ```

## RUN

``` python src/main.py ```


## Links

[github_author](https://github.com/Diegoomal)

<!-- 
[tutorial](https://www.youtube.com/watch?v=XP2sFzp2Rig)
[source_code](https://github.com/argonautcode/genetic-moth/blob/main/GeneticMoth.pde)
-->