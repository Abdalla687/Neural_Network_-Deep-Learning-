Key Components
Data Generation

Generated 1000 random samples

Each sample has 4 input features (x₁ to x₄) between -1 and 1

Output y calculated using the target function

Split into:

70% training (700 samples)

15% validation (150 samples)

15% testing (150 samples)

Neural Network Architecture

Input layer: 4 neurons (one per feature)

Single hidden layer: 50 neurons with sigmoid activation

Output layer: 1 neuron with linear activation (for regression)

Training Configuration

Loss function: Mean Squared Error (MSE) - measures prediction errors

Optimizer: Adam - adaptive learning rate algorithm

500 training epochs (full passes through the data)

Evaluation

Track validation loss during training to find optimal epoch

Final evaluation on unseen test data using RMSE

Visualize learning curves

Technical Implementation
Built using Keras/TensorFlow

Uses NumPy for data generation

Matplotlib for visualization
