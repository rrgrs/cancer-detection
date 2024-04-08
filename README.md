# Histopathologic Cancer Detection

This is a machine learning project aimed at predicting the presense of cancer given a training dataset of medical images with binary labels indicating the presense of cancer.

## Requirements

This project requires:
- Python 3.9
- [Poetry package installer](https://python-poetry.org/docs/#installation)

Ensure you have these installed before proceeding with the setup.

## Setup

To set up this project, follow these steps:

1. **Install Dependencies and Create .env File**: Run `make install`
2. **Kaggle API Key**: Go to the [Kaggle settings page](https://www.kaggle.com/settings), generate an API token, and copy the token valyes into the `.env` file. This step is necessary for accessing the Kaggle dataset.

## Run

To run the project, simply execute the following command: `make run`
This will start a Jupyter notebook server, allowing you to open and run the notebook files in your project.