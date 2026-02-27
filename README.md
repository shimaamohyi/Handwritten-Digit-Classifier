# MNIST FeedForward Neural Network (FFNN) Project

This project implements a **FeedForward Neural Network** using **PyTorch** to classify handwritten digits from the **MNIST dataset**. It covers training, validation, and visualization of performance.

---

## Project Overview

* **Dataset:** MNIST (60,000 training images, 10,000 test images of handwritten digits)
* **Goal:** Classify digits 0-9 using a simple FFNN
* **Framework:** PyTorch

---

## Model Architecture

* **Input Layer:** 28 × 28 pixels flattened into a 784-dimensional vector
* **Hidden Layers:**
  - Hidden Layer 1: 128 neurons with ReLU activation
  - Hidden Layer 2: 64 neurons with ReLU activation
* **Output Layer:** 10 neurons (digits 0-9)  
  - Softmax applied internally via `CrossEntropyLoss` in PyTorch

---

## Training Details

* **Optimizer:** Adam  
* **Loss Function:** CrossEntropyLoss  
* **Epochs:** 5  
* **Batch Size:** 64  

---

## Results

* **Final Test Accuracy:** ~97%
<img width="987" height="97" alt="Screenshot 2026-02-27 140414" src="https://github.com/user-attachments/assets/88424e6f-9142-48bf-9ac8-b83f71ffe696" />

 
 -  **Loss vs Accuracy Plot**  
   <img width="1267" height="621" alt="image" src="https://github.com/user-attachments/assets/b1c7d9bf-2870-45aa-b9fa-1e78379d1608" />

  



---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/shimaamohyi/Handwritten-Digit-Classifier
   cd Handwritten-Digit-Classifier.
