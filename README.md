# CAR_SIMULATION_USING_RL

This project simulates an AI-controlled car navigating a map using a combination of NeuroEvolution of Augmenting Topologies (NEAT) and Q-learning algorithms.

## Setup and Installation

1. Install the required libraries:
   
   %pip install pygame neat matplotlib

2. Download the project files (e.g., `car.png`, `map.png`).

3. Run the simulation:
   
   main.ipynb
   

## Project Structure

- `main.ipynb`: Main script containing the car simulation and NEAT/Q-learning logic.
- `config.txt`: Configuration file for NEAT.
- `car.png`: Image file for the car sprite.
- `map.png`: Image file for the game map.

## Usage

- The AI car is controlled by neural networks evolved using NEAT and Q-values updated with Q-learning.

## Results

- The program outputs a visual simulation of the car's navigation and saves fitness values for each generation to `OUTPUT.txt`.
- The `matplotlib` library is used to visualize fitness values over generations.
- ![image](https://github.com/user-attachments/assets/55f007d5-c9e7-408e-8c0b-43ed47f58a83)


## Future Improvements

- Implement more sophisticated neural network architectures for better AI performance.
- Add more complex maps and obstacles for the car to navigate.

## Credits

- Developed by [AKSHAT_KUMAR,ADITYA_PRAKASH]

---

