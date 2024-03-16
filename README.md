# MATH 111A_Glacier-Mass-Balance-Model

## Abstract
In recent years, the impact of global climate change has become increasingly evident, with glaciers worldwide experiencing unprecedented rates of melting. Some people suggest that there is a linear relationship between the glacier mass and temperature, while others use real data to perform regression on the relationship between factors and glacier changes. We believe that the relationship between glacier changes and climate is not simply linear and propose building a system that includes mathematical models based on the physical laws of the world for analysis of the glacier mass balance. In this project, we approach the model through the Ordinary Differential Equation (ODE) method to answer the question, "How has glacier mass balance changed over time due to temperature and precipitation?".

## Envrionment Setup
```bash
conda create -n model python=3.10
conda activate model
pip install -r requirements.txt
```

## Data Processing
The collected temperature, precipitation, and glacier mass changes data are stored in `data/`. And the code for processing the data is in `data_processing.ipynb`

## Model Solving and Plot
The code for solving the ODE model and plot the results are in `model_experiment.ipynb`.