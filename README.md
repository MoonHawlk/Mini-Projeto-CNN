# Mini-Project CNN for Fruit Recognition

## Description

This project employs Convolutional Neural Networks (CNNs) for classifying fruit images [1]. The project explores optimization techniques, regularization methods, transfer learning, and detailed result analysis.

## Authors

- André Bacelar
- Filipe Moreno
- Gabriel Costa
- Lucas Barros

## Project Structure

- **Dataset:** Fruit Recognition (Kaggle)
- **Base Model:** CNN with 3 convolutional layers, Batch Normalization, Dropout, and Weight Decay
- **Optimization:** Random Search using Keras Tuner
- **Transfer Learning:** Pre-trained ResNet50 network
- **Evaluation:** Accuracy, Precision, Recall, Confusion Matrix
- **Visualizations:** Learning curves, examples of correct/incorrect classifications

## Requirements

- Python 3.x
- TensorFlow
- Keras
- Keras Tuner
- Scikit-learn
- Matplotlib
- Seaborn

## Installation

Install the required libraries using:

```bash
pip install tensorflow keras keras-tuner scikit-learn matplotlib seaborn kagglehub
```

## Project Execution

1. Clone or download this repository.
2. Run the notebook `Mini_Atividade.ipynb` using Jupyter Notebook, Google Colab, or a similar tool.

## Step-by-Step to Reproduce Results

### 1. Dataset Download

The dataset will be downloaded automatically when running the initial notebook cells.

### 2. Data Splitting

Data is automatically split into training (70%), validation (15%), and testing (15%) sets.

### 3. Model Training

Run the notebook cells responsible for defining and training the base model.

### 4. Hyperparameter Optimization

Execute the cells related to Keras Tuner to perform optimal hyperparameter search.

### 5. Evaluation and Visualization

After training, execute the final cells to evaluate the model, generate confusion matrices, and visualize graphical results.

### 6. Pre-trained Network

Finally, run the cells implementing transfer learning with ResNet50 and compare the obtained results.

## Expected Results

- Detailed performance metrics for the base and optimized models
- Learning curves and classification examples
- Comparative analysis between the manually built model and the pre-trained network

### Dataset Information:

- **Training set size:** 16854 images (one fruit or vegetable per image)
- **Test set size:** 5641 images (one fruit or vegetable per image)
- **Number of classes:** 33 (fruits and vegetables)
- **Image size:** 100x100 pixels

## References

[1] [Fruit Recognition Dataset - Kaggle](https://www.kaggle.com/datasets/sshikamaru/fruit-recognition/data)

## License

This project is licensed under the MIT License.
