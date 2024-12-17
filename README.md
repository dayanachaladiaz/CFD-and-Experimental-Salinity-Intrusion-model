**ANALYSIS OF SALINITY INTRUSION BASED ON EXPERIMENTAL AND CFD DATA OF A SIMULATED UNCONFINED AQUIFER**

> Analyzing the experimental results of salinity intrusion in an unconfined aquifer.
> Comparing the experimental results with a numerical model created using COMSOL Multiphysics and Ansys Fluent

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#Usage)
5. [Results](#Results)
6. [License](#license)

    ---

## Overview

The experimental simulation encompassed the following five main stages: conceptualization, start of the experiment, experimental procedures, and data analysis of the
results. The first stage was the conceptualization of the model; it included selecting the
porous media, geometry, stratigraphy, initial values, and detailed assumptions considered
for each experimental assessment. It was followed by start of the experiment, including
the application of a packing technique, and adjustments of the hydraulic head and the
concentration of NaCl. The grain distribution of the porous media is presented in Figure 1,
and details of the experimental procedure are described in Table 1.

![image](https://github.com/user-attachments/assets/afde2361-6544-4138-9b30-6e39b1c56402) 
 Figure 1. Grain distribution of the fine sand.

Table 1. Details of the experimental procedures for the salinity intrusion experiments ![image](https://github.com/user-attachments/assets/76c67c2b-fedd-40f3-93a4-a81946fbe542) 

## Features

> After the experiments were developed, a numerical model was designed to explore
the capabilities of CFD platforms to recreate salinity intrusion in unconfined aquifers. 

> Both the experimental data and simulated data were analyzed using error measurements and statistical analysis. 

After you collect the experimental data and have the results from the CFD simulations, you can use my project to analyze and compare the results. It will help you identify if there is a close agreement between experiments and the numerical model.

This project offers:
- **User-Friendly Interface**:  
  Intuitive design allows users to interact with the application easily.

- **Fast and Accurate**:  
  Processes data quickly with minimal resource consumption, ensuring precise results.

- **Customizable Configurations**:  
  Users can modify parameters (e.g., input file formats, simulation settings) to suit their specific use case.

- **Supports Multiple Data Formats**:  
  Accepts input in CSV, and XML formats.

- **Visualizations**:  
  Automatically generates graphs and charts to help users interpret the results.
  
## Installation

Follow these steps to set up the project in your pc:

### 1. Prerequisites
Ensure you have the following installed:
- **Python 3.8+**
- **pip** (Python package installer)
- **Git**
- **Matplotlib**, **NumPy**, and **Pandas** (for graphing and data analysis)

### 2. Clone the repository 

git clone https://github.com/dayanachaladiaz/.git

cd 

## Usage
### 1. Organize your data

- Experimental and Simulation Data in one spreadsheet: Data.xlsx

### 2. Run the script
Scripts: 

## Results
![image](https://github.com/user-attachments/assets/428f7b71-90d2-4a45-9cdc-9e28ee6f6ad8)

![image](https://github.com/user-attachments/assets/a378531f-9d95-48a4-8d20-235a6b983b49)

* ANSYS Fluent and COMSOL software demonstrated good agreement with the experimental results, indicating the potential for CFD to replicate solute transport dynamics.
* Pilot-scale experiments allow for visualizing the saline wedge dynamics and toe
displacement over time. Both the experimental and numerical results show that the
boundary condition greatly affected the toe location over time.
* The simulation results obtained using the CFD tools and the experimental setup
provide an important step toward improving the robustness and coupling capabilities in
simulating the distribution of saltwater with other dynamics in porous media. CFD has
the potential of coupling fluid dynamics with other physics related to soil and air. It could
include assessments that consider soil dynamics, such as land subsidence and salinity
intrusion.

## License
Copyright (c) 2024 Dayana Chala

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE
