# Intrusion Detection System Using Artificial Intelligence

This repository contains the project for the **Wireless Communication and Networks** course.

## Overview

The project focuses on applying machine learning techniques to wireless communication systems, with an emphasis on anomaly detection in network traffic. It explores datasets, hierarchical modeling, and practical implementations to classify network packets and detect potential threats.

## Features

- Utilization of two datasets: **IoT-23** and **CIC-IDS** for anomaly detection.
- Final implementation leverages the **IoT-23 dataset**, compatible with **Zeek** for packet interception and analysis.
- A hierarchical model using **XGBoost** to classify packets as safe or malicious, and further identify the type of threat or attack.
- Mitigation of dataset imbalance through the hierarchical approach, enhancing anomaly detection accuracy.
- A simple dashboard displaying intercepted packets and their classifications.
- A simulation function to generate attack scenarios and log them in Zeek, testing the model's detection capabilities.

## Approach

The project is structured around a series of Jupyter notebooks and practical tools, enabling users to:

1. Understand the challenges of anomaly detection in wireless communication systems.
2. Explore the IoT-23 and CIC-IDS datasets, analyzing their characteristics.
3. Implement and evaluate the hierarchical model using XGBoost for packet classification.
4. Simulate attack scenarios and validate the model's performance in real-time using Zeek.
5. Visualize results through an interactive dashboard.

The modular design allows users to explore individual components or follow a sequential workflow.

## Usage

1. Clone the repository:
   ```bash
   git clone git@github.com:muohannedxd/ids-ai-modelling.git
   ```
2. Open the Jupyter notebooks to explore the concepts and run simulations:
   ```bash
   jupyter notebook
   ```
3. Use the provided tools to:
   - Intercept packets with Zeek and classify them using the hierarchical model.
   - Simulate attacks and observe the model's detection capabilities.
   - View packet classifications and results on the dashboard.