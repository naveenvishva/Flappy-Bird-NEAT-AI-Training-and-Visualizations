
# Flappy Bird NEAT

This Python project implements the Flappy Bird game using the NEAT (NeuroEvolution of Augmenting Topologies) algorithm. The game utilizes the pygame library for visualization and NEAT to train a neural network to play Flappy Bird.

## Project Structure
- `_pycache_`: A folder containing Python bytecode files.
- `imgs`: A folder containing images used in the game (e.g., bird, pipes, background).
- `config-feedforward.txt`: A configuration file for NEAT.
- `test.py`: The main script for running the Flappy Bird game and NEAT algorithm.
- `visualize.py`: A script to visualize the neural network and training statistics.

## Usage
1. Ensure you have Python installed along with the necessary dependencies specified in `requirements.txt`.
2. Run `test.py` to start the game and observe the NEAT algorithm training the neural network.
3. Optionally, use `visualize.py` to visualize the neural network architecture and training statistics.

## Files Description
- `test.py`: Contains the main code for the Flappy Bird game and NEAT algorithm implementation.
- `visualize.py`: Provides functions to visualize training statistics, species, and the neural network architecture.
- `config-feedforward.txt`: Configuration file for NEAT algorithm parameters.
- `imgs`: Contains images used in the game (e.g., bird, pipes, background).

## Dependencies
- Python 3.x
- Pygame
- NEAT-Python
- Graphviz (optional, for neural network visualization)

## Running the Game
To run the Flappy Bird game and observe the NEAT algorithm in action, execute `test.py`:

```bash
python test.py
```

## Visualization
You can visualize the neural network architecture and training statistics using `visualize.py`. Example usage:

```bash
python visualize.py
```

## Notes
- The NEAT algorithm is used to train a neural network to play Flappy Bird effectively.
- The project utilizes the Pygame library for game visualization.
- Make sure to provide the necessary images in the `imgs` folder for the game to function properly.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
