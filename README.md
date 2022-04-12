# Cellular Automata

This project is supposed to be a GUI application for playing around with simple
cellular automata. It should be able to model any type of generations-style
cellular automaton ([wiki page](https://conwaylife.com/wiki/Generations)).

## Goals

- [ ] GUI using Egui
- [ ] Iterations computed using compute shader
- [ ] User can change grid size
- [ ] Linear interpolation between state colours

## Steps for Calculating an Iteration

1. Count neighbours for each cell
2. If neighbours == born, cell = num_states
3. Count neighbours
4. If neighbours not in survive && cell > 0, cell -= 1
