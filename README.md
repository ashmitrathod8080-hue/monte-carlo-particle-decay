# monte-carlo-particle-decay
Monte Carlo simulation modeling radioactive particle decay, visualizing decay curves using Python.

## Overview
This project implements a **Monte Carlo simulation** to model the statistical nature of **radioactive particle decay** over discrete time steps.  
It applies **probability theory** and **randomized numerical methods** to approximate physical decay processes, generating results that align with the theoretical exponential decay law.

The simulation demonstrates how **stochastic methods** can be applied in **computational physics** — a core skill used in modern scientific research, including particle physics experiments at CERN.

## Features
- Models **radioactive decay** using random number generation
- Adjustable parameters:  
  - Initial particle count  
  - Probability of decay per step  
  - Total simulation time steps
- Visualization of **decay curves** using `Matplotlib`
- Easily adaptable for other **probabilistic processes**

## Scientific Background
Radioactive decay is inherently probabilistic — each particle has a constant probability of decaying per unit time.  
The **Monte Carlo method** simulates many random decay events to approximate expected outcomes.  
Such simulation techniques are widely used at CERN in **high-energy physics**, **detector simulations**, and **statistical uncertainty analysis**.

The simulation output follows the **exponential decay law**:

\[
N(t) = N_0 e^{-\lambda t}
\]

Where:
- \( N(t) \) = particles remaining at time \( t \)  
- \( N_0 \) = initial number of particles  
- \( \lambda \) = decay constant

## Technologies Used
- **Python 3**
- **NumPy** – for fast numerical array operations
- **Matplotlib** – for scientific plotting

## Installation & Usage

### 1. Clone the Repository
git clone https://github.com/yourusername/monte-carlo-particle-decay.git
cd monte-carlo-particle-decay

### 2. Install Dependencies
pip install numpy matplotlib

### 3. Run the Simulation
python decay_simulation.py


## Example Output

The simulation produces a decay curve showing the number of remaining particles at each time step:
<img width="1600" height="1000" alt="screenshot" src="https://github.com/user-attachments/assets/30034690-dcbe-4f10-aa68-5a165583be44" />


#Possible Extensions

Calculate and display the theoretical decay curve alongside the simulated one

Allow multiple decay channels with different probabilities

Store simulation data to CSV for further analysis

Author

Ashmit Rathod  – B.E Computer Science student at KLE Technological University, Belagavi
Interests: Computational Physics, AI/ML, Scientific Computing, Data Analysis
