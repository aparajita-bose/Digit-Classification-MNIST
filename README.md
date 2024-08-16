# Digit-Classification-MNIST
This is a simple two layer CNN (ConvNet) model to classify digits (0-9) from MNIST dataset.

## How to Run?

### Environment Setup

The code was tested in MacBook Pro with Apple M1 Pro processor with Conda environment in VSCode.

1. Install Conda [[ref](https://pytorch.org/get-started/locally/#anaconda)]:
    ```
    curl -O https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-arm64.sh
    sh Miniconda3-latest-MacOSX-arm64.sh
    ```
2. Create Conda environment from the provided `environment.yml`:
    ```
    conda env create -f environment.yml
    ```
3. Use `digit-classification` Conda environment in VSCode.


### Run the Model

1. **Training:** Run the notebook [handwritten_digit_CNN.ipynb](handwritten_digit_CNN.ipynb) for training the model.
2. **Testing:** Run the notebook [user-test-digits.ipynb](user-test-digits.ipynb) for testing. You can use also your own handwritten-digit (0-9) images for testing. 

## Reference
I found the original notebook from this link: https://github.com/trekhleb/machine-learning-experiments, I contribute few hand written testing inputs from 0 to 9 on my own. 

Thanks to the author for sharing open-source code and explanation: https://github.com/trekhleb
