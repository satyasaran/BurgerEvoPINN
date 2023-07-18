
# Deep Learning Based Solution of Nonlinear Partial Differential Equations Arising in the Process of Arterial Blood flow 
 Under review in Mathematics and Computers in Simulation
# Authors
 Bivas Bhaumik, Soumen De, and Satyasaran Changdar: 


## Table of Contents

- [Abstract](#abstract)
- [Usage](#usage)
- [Data](#data)
- [Contributing](#contributing)
- [Installation](#installation)


## Abstract


This work introduces a Python implementation using DeepXDE, a deep learning library for solving partial differential equations (PDEs). The proposed deep learning approach analyzes perturbations in arterial blood flow,
with a focus on pressure and radius variations. The research develops a mathematical model for simulating viscoelastic arterial flow, incorporating long wavelength and large Reynolds number assumptions. Leveraging the
reductive perturbation method, the study derives nonlinear evolutionary equations for medium resistance, elastic properties, and wall viscosity. By employing state-of-the-art physics-informed deep neural networks,
trained via automatic differentiation, the implementation efficiently solves these equations. Bayesian Hyperparameter Optimization identifies the optimal neural network architecture, providing an efficient and accurate
alternative to numerical methods for medical machine learning applications.


## Usage

Open the Burger_Bayesian.ipynb/Evol_Bayesian.ipynb notebook in Jupyter Notebook or any compatible notebook application and Burger_sin.ipynb/Evol_4th_order_Sin.ipynb for rest of the results. Run the notebook cells in sequential order to execute the code and reproduce the some of the results of the work. Other results can be obtained similary.
Feel free to modify the code, experiment with for hyperparameter tuning and  different machine learning models or techniques, and explore the results.
## Data
Data used in this work are described in the Manuscript


## Contributing
Contributions to this project are welcome! If you find any issues, have suggestions, or would like to add new features, feel free to open an issue or submit a pull request.

## Installation

To set up the project locally, follow these steps:

```shell
git clone https://github.com/satyasaran/BurgerEvoPINN.git
cd BurgerEvoPINN.git
python -m venv env
source env/bin/activate (for Linux/Mac)
env\Scripts\activate (for Windows)
pip install -r requirements.txt
Once the dependencies are installed, you can proceed to the usage section above to run the code. ```

