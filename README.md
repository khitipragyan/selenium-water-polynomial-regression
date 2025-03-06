# Prediction of Anaerobic Digestion of Selenium-Contaminated Wastewater using Polynomial Regression

## Overview
Anaerobic digestion is a biological process used for treating wastewater and removing contaminants. This project focuses on applying **Polynomial Regression** to predict the effectiveness of anaerobic digestion systems treating **selenium-contaminated wastewater**. Selenium is a heavy metal that is toxic at elevated concentrations and requires remediation. The model analyzes parameters such as temperature, pH, organic load, and selenium concentration to optimize the bioremediation of selenium through the prediction of the selenium digestion rate (lambda).

## Process Explanation
Anaerobic digestion is a biological treatment process where microorganisms break down organic matter in the absence of oxygen. When selenium-contaminated wastewater is treated through anaerobic digestion, the primary focus is on selenium bioremediation:

**Selenium Bioremediation**: Specialized microorganisms can convert toxic forms of selenium (selenate and selenite) into less toxic elemental selenium (Se⁰) or volatile forms. This biochemical reduction of selenium is crucial for environmental protection and is characterized by the selenium digestion rate (lambda).

The challenge lies in optimizing the process parameters to maximize selenium removal efficiency under various conditions.

## **Role of Polynomial Regression in Prediction**
The relationship between process parameters and selenium digestion efficiency is highly nonlinear. Polynomial Regression helps by:
* Modeling complex interactions between selenium concentration and digestion rate (lambda)
* Predicting selenium removal efficiency under various operating conditions
* Identifying optimal parameters that maximize selenium bioremediation
* Accounting for potential inhibitory effects of high selenium concentrations on anaerobic microorganisms

## Features
* **Data Preprocessing**: Cleans and normalizes selenium-contaminated wastewater treatment data
* **Polynomial Regression Model**: Predicts selenium digestion rate (lambda) based on selenium concentration and other parameters
* **Visualization**: Graphs showing the relationship between selenium concentration and treatment efficiency (lambda)
* **Evaluation Metrics**: Uses RMSE, R² score, and MAE to assess model accuracy

## Expected Outcomes
* Predictive model showing the relationship between selenium concentration and digestion rate (lambda)
* Identification of optimal operating conditions for selenium bioremediation
* Quantification of selenium inhibition thresholds for microbial activity
* Insights into microbial adaptation to selenium presence over time

## Dataset
The dataset used in this study was taken from:
*Logan, Mohanakrishnan. "Anaerobic digestion of selenium-rich wastewater for simultaneous methane and volatile fatty acid production and selenium bioremediation." Supervisor: Prof. Piet N. L. Lens. A thesis submitted to the National University of Ireland, Galway (NUI Galway), in fulfillment of the requirements for the degree of Doctor of Philosophy (PhD).*

## Installation
**Prerequisites**  
Ensure you have Python 3.6+ installed along with the required libraries.

**Install Dependencies**
```bash
pip install numpy pandas matplotlib scikit-learn
```
