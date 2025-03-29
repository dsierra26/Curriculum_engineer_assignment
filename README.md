# Breast Cancer Classification with Neural Networks

This repository contains a Jupyter Notebook that guides users through training a neural network to classify breast cancer cases using the Breast Cancer Wisconsin dataset. The project is containerized with Docker for easy execution.

## Repository
GitHub: [Breast Cancer Classification](https://github.com/dsierra26/Curriculum_engineer_assignment)

## Requirements
- Docker installed on your machine

## How to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/dsierra26/Curriculum_engineer_assignment
   cd Curriculum_engineer_assignment
   ```
2. Build the Docker image:
   ```sh
   docker build -t breast-cancer-classification .
   ```
3. Run the container:
   ```sh
   docker run -p 8888:8888 breast-cancer-classification
   ```
4. Open Jupyter Lab by copying and pasting the provided URL from the terminal into your browser.

## Project Structure
- `CE_assignment.ipynb`: Jupyter Notebook with the classification task.
- `Dockerfile`: Defines the environment setup.
- `requirements.txt`: Lists the required Python dependencies.

## Dataset
The dataset used is the Breast Cancer Wisconsin dataset from `sklearn.datasets`. It consists of features computed from digitized images of breast masses and a binary classification label indicating whether the tumor is malignant or benign.

## Objective
The goal is to train a neural network that achieves over 85% validation accuracy in classifying breast cancer cases.