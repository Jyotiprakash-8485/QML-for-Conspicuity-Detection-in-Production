# QML-for-Conspicuity-Detection-in-Production
Womanium Quantum+AI 2024 Projects

**Please review the participation guidelines [here](https://github.com/womanium-quantum/Quantum-AI-2024) before starting the project.**

_**Do NOT delete/ edit the format of this read.me file.**_

_**Include all necessary information only as per the given format.**_

## Project Information:

### Team Size:
  - Maximum team size = 2
  - While individual participation is also welcome, we highly recommend team participation :)

### Eligibility:
  - All nationalities, genders, and age groups are welcome to participate in the projects.
  - All team participants must be enrolled in Womanium Quantum+AI 2024.
  - Everyone is eligible to participate in this project and win Womanium grants.
  - All successful project submissions earn the Womanium Project Certificate.
  - Best participants win Womanium QSL fellowships with Fraunhofer ITWM. Please review the eligibility criteria for QSL fellowships in the project description below.

### Project Description:
  - Click [here](https://drive.google.com/file/d/1AcctFeXjchtEhYzPUsHpP_b4HGlI4kq9/view?usp=sharing) to view the project description.
  - YouTube recording of the project description - [link](https://youtu.be/Ac1ihFcTRTc?si=i6AIVfQQh8ymYQYp)

## Project Submission:

To begin, the project required completing five tasks, but I could only finish four.

**1. Task-1-: Getting Familiar with Pennylane Codebook**

To kick things off, start with task 1, which can be found in this repository. This will help you to dive into the world of quantum computing with this hands-on PennyLane codebook project! We'll delve into the foundational concepts, starting with the enigmatic qubit and its mind-bending properties, such as superposition. You'll learn to manipulate these qubits using quantum gates, the fundamental components of quantum circuits. We'll delve into essential single-qubit gates like the Pauli X and Hadamard and then progress to multi-qubit circuits that unleash even more computational power. By the end, you'll be using PennyLane to build and simulate your own quantum algorithms, gaining a solid grasp of how this exciting technology operates. 
The file can be found in this repo or [here](https://colab.research.google.com/drive/1q_RwcN7dQW9Z_-MsyuyJq94VDzftILhT?usp=sharing).

**2. Task-2(A)-: Parity Function with Variational Circuit**

This task demonstrates the use of a variational quantum circuit to learn and emulate the parity function. The circuit is trained using a binary classification approach, where the goal is to predict whether a given binary input has an even or odd number of '1s. 

Key aspects of this implementation include:

- **Basis Encoding:** Binary inputs are encoded directly into the initial state of the quantum circuit.
- **Variational Circuit:** A layered structure of rotation and CNOT gates forms the variational circuit, whose parameters are optimized during training.
- **Optimization:** The Nesterov Momentum Optimizer is used to adjust the circuit parameters and minimize the mean squared error loss.
- **Evaluation:**  The trained model is evaluated on a test dataset to assess its generalization performance.

This example highlights the potential of variational quantum circuits for learning complex boolean functions and provides a foundation for exploring more advanced quantum machine learning applications. The file can be found in this repo or here(https://colab.research.google.com/drive/1-camys0Niffep1wBff4LDOzV0sdgIXZf?usp=sharing).

**3. Task-2(B)-: Iris Classification with Quantum Machine Learning**

This Jupyter Notebook demonstrates the application of quantum machine learning techniques to classify the Iris dataset. The notebook covers the following key aspects:

- **Quantum State Preparation:** We utilize a quantum state preparation routine to encode classical data into a quantum state. The encoding scheme is based on established quantum computing principles for efficient data representation.
- **Variational Quantum Classifier:** A variational quantum circuit is constructed, comprising parameterized quantum gates and entanglement operations. The circuit takes the prepared quantum state as input and produces an expectation value used for prediction.
- **Classical-Quantum Integration:** The output of the quantum circuit is combined with a classical bias term to generate the final classification prediction. This step seamlessly integrates the quantum and classical components of the model.
- **Training and Evaluation:** The model is trained using a NesterovMomentumOptimizer to minimize the square loss between predicted and true labels. The performance of the classifier is assessed on both training and validation sets using accuracy metrics.
- **Visualization:** The notebook includes visualizations of the original data, transformed data, feature vectors, and decision boundaries. These plots provide insights into the data transformations and the classification performance of the model.

This example showcases the potential of quantum machine learning for solving classification problems and provides a foundation for exploring more complex quantum machine learning applications. The file can be found in this repo or [here](https://colab.research.google.com/drive/1cPi5V4e9nmQsMwRfH-wdSQOypcnbFI6R?usp=sharing).

**4. Task-3-: Quanvolution**

This file demonstrates a hybrid quantum-classical approach to image classification using a quantum convolutional neural network (QCNN). The core idea is to leverage a quantum circuit to perform a convolution-like operation on the input image, extracting features that are then fed into a classical neural network for classification.

- **Quantum Convolution:** A quantum circuit is defined to encode a small portion of the input image (a 2x2 square) using parameterized rotations. A random quantum circuit is then applied, followed by measurements to obtain expectation values. These expectation values are treated as features extracted from the image.
- **Preprocessing:** The entire training and test datasets are preprocessed using this quantum convolution operation. This step essentially embeds quantum-derived features into the image data.
- **Classical Model:** A simple classical neural network consists of a flattening layer and a dense layer with softmax activation. This model takes the quantum preprocessed images as input.
- **Training and Comparison:** The classical model is trained on both the quantum preprocessed data and the original MNIST data. The performance (validation accuracy and loss) of both models is then compared to assess the impact of the quantum convolution layer.

By comparing the performance of the two models, one can investigate whether the quantum convolution layer provides any advantage in terms of classification accuracy or learning efficiency. This approach explores the potential of combining quantum and classical machine learning techniques for image processing tasks. The file can be found in this repo or [here](https://colab.research.google.com/drive/1I8EDeShjcXoC9SrylTJLl50t0djhpKuM?usp=sharing).

**5. Task-4-: Quantum Machine Learning for Sine Function Approximation**

This Jupyter Notebook demonstrates the application of Quantum Machine Learning (QML) to approximate the sine function. It leverages the PennyLane library to construct a quantum circuit capable of learning the relationship between input values and their corresponding sine values.

- **Data Generation:** We generate training and test datasets consisting of input values within a specified range and their corresponding sine values.
- **Quantum Circuit Design:** A quantum circuit is defined using PennyLane, incorporating parameterized quantum gates (RX, RY, RZ) to process input data and produce an output.
- **Cost Function Definition:** A cost function (mean squared error) measures the discrepancy between the model's predictions and the actual sine values.
- **Optimization:** The Gradient Descent Optimizer iteratively adjusts the circuit parameters to minimize the cost function.
- **Training and Evaluation:** The model undergoes training, with periodic assessments of its performance on the test dataset using an accuracy metric.
- **Visualization:** The final results, including training data, test data, and model predictions, are presented in a scatter plot for visual analysis.

This notebook provides a practical example of how quantum computing can be harnessed for machine learning tasks, offering a glimpse into the potential of QML for solving complex problems. The file can be found in this repo or [here](https://colab.research.google.com/drive/1iIQiIO3dO04EMnae4mXruvEGpJ77WuU1?usp=sharing).

### Team Information:
Team Member 1:
 - Full Name: **Jyotiprakash Parhi**
 - Womanium Program Enrollment ID: **WQ24-OEoK5YQZOHWXRWG**


### Project Solution:
_Include a comprehensive summary of all important information about your project solution here._
All necessary code files and any additional information required to judge your project solution should be included in the repository. 

### Project Presentation Deck:
_Upload/ Link a 3min. presentation deck here._

See project presentation guidelines [here](https://docs.google.com/document/d/13nWF8AxFAfFYTWEYPT3BpPdYkqtxxSAjmuXj_zcMh-E/edit?usp=sharing)

