# CVRP-Genetic-Algorithm
The aim of this project is to implement a genetic algorithm to optimise solutions for the capacitated vehicle routing problem (CVRP).

The developed genetic algorithm utilises:
- Both randomised and nearest neighbour initial population generation.
- Double-elitist parent selection.
- Adjusted OX crossover alongside both inversion and swap sequence mutations.
- An intermittent 2-opt swap local search heuristic.

Three problem instances, sourced [here](http://vrp.atd-lab.inf.puc-rio.br/index.php/en/)<sup>1</sup>, are provided as examples.

<sup>[1]</sup> Uchoa, E., Pecin, D., Pessoa, A., Poggi, M., Vidal, T., Subramanian, A., 2017. New benchmark instances for the Capacitated Vehicle Routing Problem. European Journal of Operational Research 257, 845–858. https://doi.org/10.1016/j.ejor.2016.08.012
