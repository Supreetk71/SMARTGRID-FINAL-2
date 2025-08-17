This repository contains the final version 2 of the Smart Grid project. The project focuses on simulating and managing a smart electrical grid system, incorporating features like energy distribution optimization, renewable energy integration, and demand-response mechanisms. It aims to provide a framework for analyzing and improving the efficiency of modern power grids.
Features

Simulation Engine: Models energy production, consumption, and distribution in a grid network.
Optimization Algorithms: Uses techniques like linear programming to optimize energy flow and reduce costs.
Renewable Integration: Supports solar, wind, and other renewable sources with variability modeling.
User Interface: Basic dashboard for visualizing grid status and performance metrics.
Data Analysis: Tools for analyzing historical data and predicting future demands.

Technologies Used

Python 3.x
Libraries: NumPy, Pandas, Matplotlib, SciPy, PuLP (for optimization)
Optional: PyGame for visualizations (if applicable)

Installation

Clone the repository:
textgit clone https://github.com/Supreetk71/SMARTGRID-FINAL-2.git

Navigate to the project directory:
textcd SMARTGRID-FINAL-2

Install dependencies:
textpip install -r requirements.txt
(If requirements.txt is not present, install manually: pip install numpy pandas matplotlib scipy pulp)

Usage

Run the main simulation script:
textpython main.py

Configure parameters in config.json or via command-line arguments.
View results in the generated plots or console output.

Example:
textpython simulate_grid.py --input data/grid_data.csv --output results/
Project Structure

src/: Source code files

simulation.py: Core simulation logic
optimization.py: Optimization modules
visualization.py: Plotting and UI functions


data/: Sample datasets for grid configurations
docs/: Additional documentation
tests/: Unit tests

Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes. Ensure to follow the code style and add tests for new features.
License
This project is licensed under the MIT License - see the LICENSE file for details.
Contact
For questions or suggestions, contact Supreetk71 via GitHub issues.
