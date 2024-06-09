# GANs in Action - Pixel Art Generator

This project is based on the book *GANs in Action*, specifically Chapter 4, but it uses a different dataset from [Kaggle - Pixel Art Dataset](https://www.kaggle.com/datasets/ebrahimelgazar/pixel-art).

## Overview

The project involves training a Generative Adversarial Network (GAN) to generate pixel art images. The code is used for a presentation in the course "Aktuelle Themen der KI" at the Deggendorf Institute of Technology, as part of the AI Bachelor's program in the 6th semester.

## Dataset

The dataset used in this project is sourced from Kaggle:
- **Dataset**: [Pixel Art Dataset](https://www.kaggle.com/datasets/ebrahimelgazar/pixel-art)

## Requirements

- Python 3.11
- TensorFlow
- NumPy
- Matplotlib
- tqdm

You can install the required packages using the following command:

```bash
pip install requiremenets.txt
```

## Project Structure
- `code_demo.ipynb`: This Jupyter Notebook contains the code used for the presentation in the course "Aktuelle Themen der KI".
### Training the GAN
The GAN consists of a generator and a discriminator model. The training process involves alternating between training these two models.

#### Key Steps:
1. **Load and preprocess the dataset:**  
    - Normalize pixel values to the range [-1, 1].
2. **Create the models:**  
    - Define the generator and discriminator models.
3. **Define the loss functions and optimizers:**
    - Use the Adam optimizer for both models.
4. **Training:**
    - Train the models using the preprocessed dataset.
    - Save generated images at each epoch for visualization.


### Running the Project
To run the project, open the `code_demo.ipynb` notebook and follow the instructions provided in the cells. The notebook contains all the necessary code and explanations to understand the training process and visualize the results.