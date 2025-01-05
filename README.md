# Bot and Rat Tracking Simulation

This repository contains a simulation project for a bot and rat tracking environment using a grid system. The project implements various classes for environment simulation, bot and rat behavior, probabilistic detection, and knowledge management.

## Project Structure

The repository includes the following files:

- `main.ipynb` - The main file to run the simulation. Includes code to import other modules and execute the simulation.
- `bot.py` - Contains the implementation of the bot, including its movement, detection, and tracking logic.
- `knowledge_base.py` - Manages and filters the bot's knowledge about its location in the grid environment.
- `rat.py` - Implements the rat's behavior and movements in the grid.
- `rat_knowledge_base.py` - Manages the rat's knowledge and its interaction with the bot.
- `rat_bot_model.keras` - Pre-trained Keras model used for probabilistic detection and decision-making.
- `ship_environment.py` - Defines the grid environment, including blocked and open cells.
- `simulation.py` - Simulates the interaction between the bot and rat in the environment.
- `.ipynb_checkpoints/` and `__pycache__/` - Auto-generated directories for Jupyter Notebook checkpoints and Python cache files.

## Prerequisites

- Python 3.8 or higher
- Install the required dependencies using `pip`:



