# Estimate CO2 from Cars


This code comes from a Kaggle challenge aiming to predict carbon dioxide (CO2) emissions from vehicles using a dataset that includes detailed information on various aspects of the vehicles.

The data used in this challenge is available at the following address:
[Estimate CO2 from cars](https://www.kaggle.com/competitions/estimate-co2-emissions-from-cars)
## Installation

To ensure an isolated development environment, we recommend using a virtual environment (venv). Follow these steps to create your virtual environment and install the project dependencies:

1. Clone the github repository
```bash
git clone https://github.com/AxelFritz2/Challenge_Kaggle_Mosef.git
cd Challenge_Kaggle_Mosef
```
2. Create a virtual environment
```bash
python -m venv venv
```

3. Activate the virtual environment

- On Windows : 
    ```bash
  .\venv\Scripts\Activate
    ```
- On Linux/Mac
    ```bash
  source venv/bin/activate
    ```

4. Install the dependencies

```bash
pip install -r requirements.txt
```

## Project Structure
- **src**: The project source code, this folder includes the data preprocessing script.
- **notebooks**: This folder contains Jupyter notebooks used for exploratory data analysis and all the models used in this project.
- **artefacts**: This folder includes all the artifacts (models and hyperparameters) saved for reuse without retraining the various models.
- **requirements**: The list of project dependencies.


## Authors

- [Samuel Launay Pariente](https://github.com/samuel-LP)
- [Samuel Baheux](https://github.com/SamuelBaheux)
- [Axel Fritz](https://github.com/AxelFritz1)
