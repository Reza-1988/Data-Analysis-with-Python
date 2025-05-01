# NumPy Play with Quera

![Python](https://img.shields.io/badge/Python-3.8%2B-blue) ![NumPy](https://img.shields.io/badge/NumPy-1.21%2B-orange) ![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4%2B-green) ![License](https://img.shields.io/badge/License-MIT-yellow)

Welcome to **NumPy Play with Quera**, a hands-on data analysis project designed to deepen your understanding of NumPy array manipulation through an engaging exercise. This project involves splitting and concatenating arrays to reconstruct the Quera logo, offering both a practical challenge and a visual reward.

## Project Overview
This project is a Jupyter Notebook-based exercise that guides you through manipulating a NumPy array representing the Quera logo's color channels. You'll load a dataset, split it into three parts, and recombine them to reconstruct the logo. The project is structured to allow you to solve it independently and then compare your work with provided solutions.

The dataset is stored in `data.npz`, and explanatory images (`image1.jpg`, `image2.jpg`) help illustrate the array operations. By the end, you'll visualize the results using Matplotlib, revealing the connection between the data and the Quera logo.

## Features
- **Interactive Learning**: Solve array manipulation tasks step-by-step in a Jupyter Notebook.
- **Visual Feedback**: Visualize individual color channels and the final reconstructed Quera logo.
- **Modular Structure**: Separate data and solution folders to encourage independent problem-solving.
- **Well-Documented**: Clear instructions and diagrams to guide users through the exercise.

## Folder Structure
numpy-play-with-quera/
│
├── data/
│   ├── data.npz           # Input dataset (506x1500x1 array)
│   ├── image1.jpg         # Diagram for Part One
│   └── image2.jpg         # Diagram for Part Two
│
├── solution/
│   └── play_with_quera_solution.ipynb  # Complete solution to the exercise
│
├── play_with_quera.ipynb  # Main Jupyter Notebook for the exercise
│
└── README.md              # Project documentation


- **`data/`**: Contains the dataset (`data.npz`) and images used for explanation.
- **`solution/`**: Includes the solved notebook for reference after attempting the exercise.
- **`play_with_quera.ipynb`**: The main notebook where you solve the tasks.

## Installation
To run this project, you need Python 3.8+ with the following dependencies:

- `numpy>=1.21`
- `matplotlib>=3.4`
- `jupyter>=1.0`

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Reza-1988/Data-Analysis-with-Python.git
   cd numpy-play-with-quera
