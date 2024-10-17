# Fraud Detection using PySpark and Random Forest

This project demonstrates a fraud detection system using a large dataset (6,362,620 rows and 10 columns) to identify fraudulent transactions. The dataset is processed using PySpark, and a Random Forest classifier is applied to achieve an accuracy of 97% using a generalized model.

## Table of Contents
- [About the Project](#about-the-project)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Model Overview](#model-overview)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About the Project

The objective of this project is to build a high-performance fraud detection model that can efficiently process a large dataset using distributed computing (PySpark). The Random Forest algorithm is used to capture complex patterns in the data and provide accurate predictions.

### Key Features:
- **Large-scale data processing** using PySpark for efficient handling of millions of records.
- **Random Forest Classifier** for detecting fraud with a generalized model, achieving an accuracy of 97%.
- **Cross-validation** for hyperparameter tuning to enhance model performance.

## Dataset

The dataset used in this project contains:
- **Rows:** 6,362,620
- **Columns:** 10

### Important Features:
- `amount`: Transaction amount
- `balanceChangeOrg`: Change in balance of the origin account
- `balanceChangeDest`: Change in balance of the destination account
- `type_CASH_IN`, `type_CASH_OUT`, `type_DEBIT`, `type_PAYMENT`, `type_TRANSFER`: Transaction types
- `isFraud`: Label for fraudulent transactions (0 or 1)

## Technologies Used

- **PySpark**: For distributed data processing.
- **Random Forest**: For classification and fraud detection.
- **CrossValidator**: For hyperparameter tuning.
- **CSV**: For reading and writing data.

## Installation

### Prerequisites

- Python 3.x
- Apache Spark installed locally or access to a PySpark environment.
- Java (for Spark)
- Git (for version control)

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/King-Chirayu-2002/Fraud-Detection-using-PySpark-and-Random-Forest.git
