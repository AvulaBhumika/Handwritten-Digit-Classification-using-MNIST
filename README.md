#  Handwritten Digit Classification using MNIST

![image](https://github.com/user-attachments/assets/fd18a2de-d199-4598-96f7-861e428f640d)


This project demonstrates a handwritten digit classification pipeline using the classic **MNIST dataset**. It leverages scikit-learn, PyTorch, and Skorch to build and evaluate a neural network for classifying handwritten digits (0–9).

---

## Project Structure

- `Hand_written_text_classification.ipynb`: Jupyter Notebook containing the complete workflow.
- Uses **Skorch**, a scikit-learn compatible wrapper for PyTorch.
- Includes visualizations, training performance, and model evaluation.

---

##  Dataset

- **Source**: [MNIST Dataset](https://www.openml.org/d/554)
- **Description**: Contains 70,000 28x28 grayscale images of handwritten digits.
- **Features**: 784 pixel values (flattened 28x28)
- **Target**: Digit class labels (0 to 9)

---

##  Installation

```bash
pip install numpy matplotlib sklearn torch skorch
```

##  Model Architecture

- Built using **PyTorch**
- Trained using **Skorch** wrapper for better integration with scikit-learn workflows
- Basic MLP (Multi-Layer Perceptron) architecture

---

##  Results

- Visualizations of digit samples and predictions
- Accuracy metrics on training and validation sets
- Graphs for loss and accuracy trends over epochs

![image](https://github.com/user-attachments/assets/8ec4931c-9b15-4677-a2d8-82728e41bea4)


---

## Key Libraries Used

- `scikit-learn`
- `torch`
- `skorch`
- `matplotlib`
- `numpy`


## License

This project is open-source and available under the MIT License.
