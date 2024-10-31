This project focuses on predicting traffic speed using a custom SGCN-LSTM model, which combines a Signal-Enhanced Graph Convolutional Network (SGCN) with a Long Short-Term Memory (LSTM) network. The goal is to capture both the spatial relationships between road segments and temporal patterns in traffic data, using the PEMS-BAY dataset.

The model is implemented in PyTorch and trained to predict speeds on road segments over time. The training process includes optimizations like early stopping, learning rate scheduling, and a combined loss function with MAE and MSE for balanced accuracy. The code also provides visualization scripts to show model performance, including prediction vs. actual speed plots, residuals, and loss curves.

To get started, clone the repository, install the required packages, and run the training and evaluation scripts. The code automatically imports the PEMS-BAY dataset from torch_geometric_temporal, and generated plots and results will be saved in the root directory. The code is organized with separate directories for models, data, and visualization scripts for easier navigation.

You can adjust training parameters directly in the code, and the visualizations help analyze the model’s performance across different traffic conditions.
