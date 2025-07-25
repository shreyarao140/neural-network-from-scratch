Neural Network from Scratch (NumPy) – MNIST Digit Classification
This project demonstrates how to build a neural network from scratch using only NumPy and linear algebra, without relying on deep learning frameworks like TensorFlow or PyTorch. The model is trained to classify handwritten digits from the MNIST dataset.

📌 Features
Fully implemented feedforward neural network using NumPy

Forward propagation & backpropagation implemented from scratch

Uses gradient descent for optimization

Classifies MNIST handwritten digits (0–9)

Great for understanding the fundamentals of neural networks

🛠️ Tech Stack
Language: Python

Libraries: NumPy, Matplotlib (for visualization), pickle (for loading MNIST dataset)

📦 Installation
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/neural-network-from-scratch.git
cd neural-network-from-scratch
Install dependencies

bash
Copy
Edit
pip install numpy matplotlib
Run the training script

bash
Copy
Edit
python main.py
🔍 How It Works
Data Preprocessing – MNIST images are normalized and flattened into vectors.

Network Architecture –

Input layer: 784 neurons (28×28 pixels)

Hidden layers: Configurable (e.g., 128, 64 neurons)

Output layer: 10 neurons (digits 0–9, softmax activation)

Training – Uses cross-entropy loss & stochastic gradient descent.

Prediction – Outputs the most probable digit for a given image.

📊 Results
Achieves ~90–95% accuracy on the MNIST test set after sufficient epochs.

Visualizes training loss and accuracy over time.

📸 Sample Output
(Add a screenshot of predicted digits here if possible)

📜 License
This project is open-source and free to use for educational purposes.


