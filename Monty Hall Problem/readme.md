# Monty Hall Simulation

This project simulates the Monty Hall game, a well-known probability puzzle. The simulation includes two strategies for the contestant: **staying** with the initial door or **switching** to the other door after Monty reveals a goat behind one of the doors.

## Description

In the Monty Hall problem, a contestant is presented with three doors. Behind one of the doors is a car, and behind the other two are goats. After the contestant selects a door, Monty, who knows what’s behind each door, opens another door, revealing a goat. The contestant then has the option to switch their choice to the remaining unopened door.

The game is simulated by the function `monty_hall_game()`, and the results of multiple simulations are printed by the `simulate_games()` function, showing the winning percentages for both strategies (staying vs. switching).

## Requirements

- Python 3.x
- `random` module (included in Python standard library)

## How to Run

1. Clone or download the repository.

2. Navigate to the project directory and run the following command to start the simulation:

   ```bash
   python monty_hall.py
