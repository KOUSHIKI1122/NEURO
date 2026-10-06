# In-Silico Stem Cell Colony Simulator

An interactive cellular automaton in the browser. Click the grid to seed a colony, then run the loop and watch it grow, stabilise or die out.

**Live demo:** https://koushiki1122.github.io/stem-cell-colony-simulator/

## How to use

1. Click cells on the grid to seed the starting colony
2. Press **Trigger Loop** to start the simulation
3. Press **Wipe Matrix** to clear the grid and start again

## How it works

The rules are Conway's Game of Life: a living cell survives with 2 or 3 neighbours, an empty cell with exactly 3 neighbours comes alive, and every other cell dies or stays empty. The stem cell wording is a playful metaphor for how simple local rules can produce complex colonies.

## Built with

Plain HTML, CSS and JavaScript on a canvas. No dependencies.
