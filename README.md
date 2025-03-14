# UNSW-NB15 Intrusion Detection with Transformer Algorithm

## Overview
This project implements a deep neural network model designed to detect and classify cyber-attacks using the UNSW-NB15 dataset. The model is optimized to effectively handle imbalanced datasets, ensuring robust performance in real-world scenarios.

## Features
- Data preprocessing: Scaling numeric features, One-hot encoding categorical variables.
- Addressing class imbalance with SMOTE.
- Deep neural network architecture with Dropout and Batch Normalization.
- Evaluation metrics include Accuracy, ROC-AUC, and F1-Score.
- Visualizations: ROC Curve and Confusion Matrix for detailed performance insights.

## Dataset
The dataset used is UNSW-NB15, consisting of network traffic data designed to benchmark intrusion detection systems.
- `UNSW_NB15_training-set.csv`: Training dataset.
- `UNSW_NB15_testing-set.csv`: Testing dataset.

Place these files in the root of the project directory.

## Requirements
- Python 3.x
- TensorFlow
- Pandas
- NumPy
- Scikit-learn
- Imblearn
- Keras Tuner
- Matplotlib
- Seaborn

## Usage
Run the provided Python script to train and evaluate the model:
```bash
python your_script_name.py
```

## Results
The model outputs key metrics including Accuracy, F1-Score, ROC-AUC, and displays a confusion matrix and ROC curve for detailed analysis.

## Contributions
Contributions are welcome. Please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License.

