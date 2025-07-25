# Neural Network from Scratch (NumPy)

This project demonstrates how to build a **neural network from scratch** using only **NumPy** and linear algebra, without relying on deep learning frameworks like TensorFlow or PyTorch. 
---

## 📌 Features

- Fully implemented **feedforward neural network** using NumPy  
- **Forward propagation** & **backpropagation** implemented from scratch  
- Uses **gradient descent** for optimization  
- Classifies MNIST handwritten digits (0–9)  
- Great for understanding the **fundamentals of neural networks**

---

## 🛠️ Tech Stack

- **Language**: Python  
- **Libraries**: NumPy, Matplotlib (for visualization), Pickle (for loading MNIST dataset)

---

## 📦 Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/neural-network-from-scratch.git
   cd neural-network-from-scratch
   ```

2. **Install dependencies**  
   ```bash
   pip install numpy matplotlib
   ```

3. **Run the training script**  
   ```bash
   python nn-from-scratch.ipynb
   ```

---

## 🔍 How It Works

1. **Data Preprocessing** – MNIST images are normalized and flattened into vectors.  
2. **Network Architecture** –  
   - Input layer: 784 neurons (28×28 pixels)  
   - Hidden layers: Configurable (e.g., 128, 64 neurons)  
   - Output layer: 10 neurons (digits 0–9, softmax activation)  
3. **Training** – Uses cross-entropy loss & stochastic gradient descent.  
4. **Prediction** – Outputs the most probable digit for a given image.

---

## 📊 Results

- Achieves **~90–95% accuracy** on the MNIST test set after sufficient epochs.  
- Visualizes training loss and accuracy over time.


## 📜 License

This project is open-source and free to use for educational purposes.
