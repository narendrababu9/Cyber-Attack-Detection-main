# Cyber Attack Detection using Machine Learning

This repository contains the implementation of a machine learning model designed to detect various types of cyber attacks. The project utilizes several popular datasets including NSL-KDD, KDD Cup 99, UNSW-NB15, URL 2016, and CICIDS 2017, and employs machine learning algorithms such as Decision Trees, SVM, and Random Forest for robust cyber threat identification.

## Project Overview

The goal of this project is to develop a predictive model capable of identifying potential cyber attacks before they cause harm. By leveraging advanced machine learning techniques, this model aims to provide high accuracy and real-time threat detection.

## Datasets

This project uses the following datasets:
- **NSL-KDD**: Used for training and testing the model.
- **KDD Cup 99**: Employed for initial exploratory data analysis.
- **UNSW-NB15**: Used for training and validation.
- **URL 2016**: Utilized for specialized training on web-based attacks.
- **CICIDS 2017**: Employed across training, testing, and validation phases.

## Repository Structure

|- data/ # Folder containing datasets and preprocessing scripts
|- notebooks/ # Jupyter notebooks with exploratory data analysis and initial models
|- src/ # Source code for the machine learning models
|- tests/ # Test scripts for the ML models
|- README.md # This file
|- requirements.txt # Python package dependencies


## Installation

To set up the project environment, follow these steps:

```bash
git clone https://github.com/yourusername/cyber-attack-detection-ml.git
cd cyber-attack-detection-ml
pip install -r requirements.txt

Usage
To run the analysis notebooks, navigate to the notebooks/ directory and start Jupyter Notebook:
cd notebooks/
jupyter notebook
