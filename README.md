# Wind Power Prediction with Convolutional Neural Networks

This repository contains a research project on forecasting wind energy production using Convolutional Neural Networks (CNNs). The work focuses on the Mancha Oriental region and leverages meteorological wind data to predict hourly power output.

## Introduction
Wind energy is a highly variable renewable source, making accurate forecasting essential for integrating it into the power grid. This project explores the application of CNN architectures to predict wind power based on spatial wind speed component maps.

The repository contains:
- **Trabajo_Redes_Neuronales.pdf** — The original paper *"Predicción de energía eólica con redes neuronales de convolución"*, which details the problem, dataset, methodology, and results.
- **Trabajo_RNAE.ipynb** — A Jupyter Notebook implementing the proposed CNN model using TensorFlow, from data preprocessing to training and evaluation.

## Project Overview
- **Objective:** Predict hourly average wind power production for a group of wind farms in the Mancha Oriental region.
- **Input Data:** Meteorological maps (60×60 grids) of the u and v wind components at 100 meters above ground, transformed into polar coordinates (ρ, sin(θ), cos(θ)).
- **Output:** Percentage of installed maximum capacity produced during the target hour.
- **Model:** CNN architecture with multiple convolution and pooling layers followed by a fully connected layer for regression.
- **Training:** Implemented with Adam optimizer, MAE loss, dropout regularization, and early stopping.

