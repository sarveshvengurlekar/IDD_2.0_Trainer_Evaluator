# Object Detection IDD 2.0 Trainer Evaluator

A comprehensive Jupyter Notebook-based project for training and evaluating Indian Document Detection (IDD) 2.0 models. This repository contains tools and workflows for document detection, model comparison, and performance evaluation.

## 📋 Table of Contents

- [Overview](#overview)
- [Repository Structure](#repository-structure)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Project Components](#project-components)
- [Output](#output)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

The IDD 2.0 Trainer Evaluator is a comprehensive machine learning project focused on training and evaluating models for Indian Document Detection. It provides a complete pipeline for:

- Model training on document detection tasks
- Performance evaluation and benchmarking
- Model comparison and analysis
- Integration with Kaggle datasets and Google Colab

## 📁 Repository Structure

```
IDD_2.0_Trainer_Evaluator/
├── README.md                      # Project documentation
├── Google Collab/                 # Google Colab notebook implementations
├── Kaggle IDD/                    # Kaggle dataset-based notebooks
├── Model Comparsion/              # Model comparison and analysis notebooks
├── Training Output/               # Training results and checkpoints
├── Evaluation Output/             # Evaluation metrics and results
└── .gitattributes                 # Git configuration
```

## ✨ Features

- **Model Training**: Comprehensive training pipelines for document detection models
- **Evaluation Framework**: Detailed evaluation metrics and performance analysis
- **Multi-Platform Support**: Compatible with Google Colab and Kaggle environments
- **Model Comparison**: Tools for comparing multiple model architectures and approaches
- **Output Management**: Organized storage for training and evaluation outputs

## 🔧 Requirements

- Python 3.x
- Jupyter Notebook or JupyterLab
- Common ML/DL libraries (TensorFlow, PyTorch, scikit-learn, etc.)
- Pandas, NumPy for data processing
- Matplotlib, Seaborn for visualization
- Google Colab (optional, for cloud-based execution)
- Kaggle API (optional, for dataset management)

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sarveshvengurlekar/IDD_2.0_Trainer_Evaluator.git
   cd IDD_2.0_Trainer_Evaluator
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   (Create a `requirements.txt` file with your project dependencies)

3. Set up Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## 🚀 Usage

### Local Development
1. Navigate to the project directory
2. Open Jupyter Notebook: `jupyter notebook`
3. Select the desired notebook from the respective folders
4. Run cells sequentially

### Google Colab
1. Navigate to the `Google Collab/` directory
2. Upload notebooks to Google Colab or access them directly from GitHub
3. Install dependencies in Colab cells if needed

### Kaggle Notebooks
1. Access the `Kaggle IDD/` directory
2. Use Kaggle notebook interface with the IDD dataset

## 📊 Project Components

### Google Collab/
Contains notebooks optimized for Google Colab execution with cloud-based GPU support.

### Kaggle IDD/
Notebooks utilizing Kaggle's IDD dataset with integrated Kaggle environment setup.

### Model Comparsion/
Comparative analysis notebooks for evaluating multiple model architectures, approaches, and hyperparameters.

### Training Output/
- Trained model weights
- Model checkpoints
- Training logs and metrics
- Saved model artifacts

### Evaluation Output/
- Performance evaluation results
- Confusion matrices
- Accuracy, Precision, Recall, F1 scores
- Visualization plots and graphs
- Model comparison reports

## 📈 Output

The project generates:
- **Model checkpoints** for training phase
- **Evaluation metrics** including accuracy, precision, recall, F1-score
- **Visualization reports** for performance analysis
- **Comparison matrices** for multi-model evaluation

## 🤝 Contributing

Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the MIT License. See LICENSE file for details.

---

**Author**: [sarveshvengurlekar](https://github.com/sarveshvengurlekar)

**Created**: 2026

**Language**: Jupyter Notebook (Python)
