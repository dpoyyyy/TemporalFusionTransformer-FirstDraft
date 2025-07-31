# TFT-Weather-Mockup

This is a **mockup / initial prototype** implementation of the Temporal Fusion Transformer (TFT) model for time-series forecasting. It is meant as a starting point for further development.

## Project Overview

The project focuses on applying the TFT architecture to a weather dataset. This version includes:

- Basic data preprocessing
- Simple TFT structure
- Placeholder model structure and logic

> Note: This is the **first version** and is intended for testing and planning purposes.

The original dataset used for training this model is private and is not available in this repository due to confidentiality.

## What is the Temporal Fusion Transformer (TFT)?

The Temporal Fusion Transformer is a deep learning model introduced by Google Cloud AI for interpretable high-performance multi-horizon time-series forecasting. It is designed to:

- Handle both static and time-varying inputs
- Combine LSTM-based sequence modeling with attention mechanisms
- Provide interpretable output through variable selection and attention scores
- Support multi-horizon forecasting with flexible input formats

TFT includes key components such as:
- Gated Residual Networks (GRNs) for robust nonlinear processing
- Variable selection networks for selecting relevant inputs
- Temporal self-attention layers for long-range dependencies
- Static covariate encoders

The model architecture is especially suitable for complex time-series with a mix of categorical and continuous variables, and for applications where interpretability matters.

## File Structure

- `TFT_first(max).ipynb` — Jupyter notebook containing the code mockup for the TFT model.
- `requirements.txt` — Python dependencies to run the notebook.

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/dpoyyyy/TFT-Weather-Mockup.git
   cd TFT-Weather-Mockup
   ```

2. Create a virtual environment and install requirements:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:
   ```bash
   jupyter notebook TFT_first(max).ipynb
   ```

## Notes

- This version is a **proof of concept** and will evolve.
- The dataset and hyperparameters are still under development.

## License

MIT License
