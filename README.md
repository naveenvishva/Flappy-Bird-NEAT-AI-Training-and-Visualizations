
# Flappy Bird AI using NEAT

Train an AI to play Flappy Bird using NEAT (NeuroEvolution of Augmenting Topologies).

![Flappy Bird](imgs/bg.png)

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [File Descriptions](#file-descriptions)
- [Requirements](#requirements)
- [Author](#author)
- [License](#license)

## Overview

This project implements an AI agent to play the popular game Flappy Bird. It uses the NEAT algorithm to evolve neural networks that control the bird's actions, aiming to achieve the highest score possible. The project includes scripts for training the AI (`test.py`), visualizing the training progress (`visualize.py`), and storing the configuration (`config-feedforward.txt`). Additionally, it contains image assets used in the game.

## Installation

1. Clone this repository to your local machine:
   ```
   git clone https://github.com/your_username/Flappy-Bird-AI.git
   ```

2. Navigate to the project directory:
   ```
   cd Flappy-Bird-AI
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Train the AI:
   ```
   python test.py
   ```

2. Visualize the training progress:
   ```
   python visualize.py
   ```

## File Descriptions

1. **test.py**: Script to train the AI agent using the NEAT algorithm and pygame for game simulation.

2. **visualize.py**: Script to visualize the training progress and neural network architecture.

3. **config-feedforward.txt**: Configuration file for NEAT algorithm settings.

4. **imgs/**: Folder containing image assets used in the game.

## Requirements

- Python 3.x
- NEAT-Python
- Pygame
- Graphviz (optional, for network visualization)

## Author

[Your Name/Username]

## License

This project is licensed under the MIT License - see the LICENSE file for details.
