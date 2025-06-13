# HarmonicRegression

## Description

This project explores using neural networks to model and predict a harmonic signal (a cosine wave with an added harmonic component). It compares the performance of a simple and a complex Keras model trained on data with Fourier-based noise.

## Key Features

*   Generates harmonic signals with tunable parameters.
*   Adds frequency-domain noise using Fourier transforms.
*   Compares a basic (single-layer) and a complex (multi-layer) Keras model.
*   Includes loss visualizations for model comparison.

## Usage

1.  **Prerequisites:** `pip install tensorflow numpy matplotlib`
2.  **Run the code:** Executes `harmonic_regression.py` (or similar).

## Models

*   **Basic Model:** Single-layer Keras model.
*   **Complex Model:** Multi-layer Keras model with ReLU activations.
