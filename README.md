# Stroke Prediction Project

This repository contains the code and documentation for the stroke prediction project, which utilizes machine learning to predict the likelihood of stroke incidents based on various health indicators and patient history.

## Project Overview

The goal of this project is to develop a reliable predictive model that can assist healthcare providers in identifying patients at higher risk of stroke. We employ an ETL pipeline to process our data, prepare it for analysis, and ultimately fit it into several machine learning models.

## ETL Pipeline

The ETL pipeline for this project follows these key steps:

### Extract

- Data is sourced from a secured medical database after obtaining necessary IRB approvals.
- The base directory and data files are identified, adhering to strict privacy protocols.

### Transform

- Comprehensive data cleaning and preprocessing is performed to transform the raw data into a structured format.
- This includes handling missing values, encoding categorical variables, and normalizing numerical features.

### Load

- The cleaned and processed data is then loaded into a structured format ready for model training.
- Data is stored securely, either on a protected cloud service or locally, depending on the analysis needs.

## Model Training

Several machine learning models are trained and evaluated:

- **Logistic Regression**: A baseline model for binary classification tasks.
- **Support Vector Machine (SVM)**: An advanced model capable of defining decision boundaries.
- **Multilayer Perceptron (MLP)**: A neural network approach for capturing complex patterns in the data.

## Visualization

A Directed Acyclic Graph (DAG) is provided to represent the workflow of the ETL process and the model training pipeline, illustrating the dependencies and order of operations.

## Usage

Instructions for setting up the environment, running the ETL pipeline, and training the models are provided in the respective scripts within this repository.

## Contributing

This project is part of my ongoing research as a PhD student with an interest in improving healthcare outcomes using Machine Learning and AI. Contributions, suggestions, and inquiries are welcome.

## Contact

For further information or to discuss collaboration opportunities, please contact me at m.tamakloe@wustl.edu

## Acknowledgements

Special thanks to my academic advisors and the data science team for their guidance and support throughout this project.

## License

This project is licensed under the [Appropriate License] - see the LICENSE.md file for details.

