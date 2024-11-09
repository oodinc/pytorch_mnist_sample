# pytorch_mnist_sample

**The goals of this assignment are:**
- Students have GitHub accounts and repositories.
- Understand git workflow, branching strategy, and pull requests.
- Students could make code collaboration.

## Getting started

Follow the steps below to fork, clone, and run this project on Google Colab to meet the assignment requirements.

### Prerequisites

- A GitHub account to fork and clone the repository.
- Google Colab or a local Python environment with PyTorch and torchvision installed.

### Installation Steps

1. **Fork and Clone Repository**:
- Fork this public repository: [https://github.com/Rietaros/pytorch_mnist_sample](https://github.com/Rietaros/pytorch_mnist_sample).
- Clone the forked repository to your local machine:
```bash
git clone https://github.com/YOUR_USERNAME/pytorch_mnist_sample.git
```
- Navigate to the project directory:
```bash
cd pytorch_mnist_sample
```

2. **Run in Google Colab**:
- Open the `pytorch-mnist.ipynb` file in Google Colab.
- Run each cell to train the model and check the accuracy results.

## Hyperparameter Modification

To achieve accuracy above 90%, modify the hyperparameters `learning_rate` and `momentum` in `pytorch-mnist.ipynb` as follows:

- **Default Value**:
```python
learning_rate = 0.1
momentum = 0.00003

- **Modified Value**:
```python
learning_rate = 0.001
momentum = 0.99

### Create a New Branch and Commit Changes

1. **Create a New Branch**:
```bash
git checkout -b parameter-testing
```
2. **Add and Commit Changes**:
```bash
git add pytorch-mnist.ipynb
git commit -m "Update learning rate and momentum for optimizer"
```
3. **Push Changes**:
```bash
git push origin parameter-testing
```

### Creating a Pull Request

1. **Open your forked repository on GitHub.**
2. **Click the "Compare & pull request" button next to the parameter-testing branch.**
3. **Add a title and description for your pull request, then click "Create pull request".**
