# Deep Neural Networks: Activation Function Comparison

This project explores the performance of different activation functions (Sigmoid, Tanh, and ReLU) in deep neural networks on the MNIST dataset. It compares training loss and validation accuracy to analyze the impact of activation functions on learning and generalization.

---

## **Objective**
1. Define neural networks with Sigmoid, Tanh, and ReLU activation functions.
2. Train the models on the MNIST dataset.
3. Analyze and compare training loss and validation accuracy.

---

## **Dataset**
- **MNIST**: Handwritten digit dataset.
  - Training Set: 60,000 samples.
  - Validation Set: 10,000 samples.
- Images are transformed into tensors for input to the neural networks.

---

## **Implementation**
- **Neural Networks**: Three models with two hidden layers:
  - **Sigmoid**: `torch.sigmoid`
  - **Tanh**: `torch.tanh`
  - **ReLU**: `torch.relu`
- **Optimizer**: SGD with a learning rate of 0.01.
- **Loss Function**: CrossEntropyLoss.

---

## **Results**
- Training loss and validation accuracy are compared across activation functions.
- ReLU often demonstrates faster convergence and better accuracy.

---

## **How to Run**
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
