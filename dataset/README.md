# Hepatocellular Carcinoma (HCC) Survival Prediction

This project aims to predict the survival outcome (Dies or Lives) of patients with Hepatocellular Carcinoma (HCC) using various machine learning models. The dataset used contains medical and demographic information about the patients.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Introduction

Hepatocellular Carcinoma (HCC) is a common type of liver cancer. This project uses machine learning techniques to predict whether a patient with HCC will survive or not based on their medical and demographic data.

## Dataset

The dataset used in this project is `hcc_dataset.csv`, which contains the following information:
- Medical history and demographic data of patients
- Various medical test results
- Survival outcome (Dies or Lives)

## Dependencies

The project requires the following Python libraries:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

You can install the dependencies using `pip`:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Project Structure

- `Checkpoint1.ipynb`: Jupyter notebook containing the code for the project.
- `hcc_dataset.csv`: Dataset used for the project.

## Usage

1. **Clone the repository**:

```bash
   git clone https://github.com/your-username/HCC-Survival-Prediction.git
   cd HCC-Survival-Prediction
```

2. **Install dependencies**:

```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
```

3. **Run the Jupyter Notebook**:

   Open `Checkpoint1.ipynb` in Jupyter Notebook or Jupyter Lab and execute the cells to run the project.

## Results

The project evaluates three machine learning models:
- Random Forest
- Decision Tree
- K-Nearest Neighbors (KNN)

The models are evaluated based on the following metrics:
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)
- ROC Curve and AUC

### Model Comparison

A summary table and bar chart compare the performance of the three models based on the evaluation metrics mentioned above.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

This README provides an overview of the project, including its purpose, dataset, dependencies, usage instructions, and evaluation results. If you have any questions or issues, please feel free to open an issue on GitHub.

---

**Note**: Remember to update the GitHub URL and other placeholders with actual values specific to your project.
