# Stress-Testing CNNs on CIFAR-10 (Group 16)
This project investigates the behavior of Convolutional Neural Networks beyond raw accuracy using the CIFAR-10 dataset.

The baseline model is a modified ResNet-18 trained from scratch. According to the accompanying report DL_group16_assignment_1, the study examines high-confidence misclassifications and demonstrates how a simple change (L2 weight decay) can improve calibration and generalization without major accuracy gains.

Install the dependencies mentioned in requirements.txt before running.
*GPU recommended for faster training

# How to Run
Option 1 — Run in Jupyter Notebook / JupyterLab
1. Open terminal in the project folder
2. Launch Jupyter:
jupyter notebook
3. Open:
DL_Assignment.ipynb
4. Click:
Kernel → Restart & Run All

Option 2 — Run in Google Colab (Recommended)
1. Upload the notebook to Colab
2. Enable GPU:
Runtime → Change runtime type → GPU
3. Run all cells sequentially
