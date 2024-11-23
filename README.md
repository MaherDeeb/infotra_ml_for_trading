# ML for Trading with [Infotra.io](https://services.infotra.io/)

![Infotra.io Logo](./images/infotra.png)

Welcome to the ML for Trading with [Infotra.io](https://services.infotra.io/) Repository! This repository contains Jupyter Notebooks designed to demonstrate how to
use [Infotra.io](https://services.infotra.io/) for machine learning (ML) applications in trading. 
Whether you're a trader, data scientist, or ML enthusiast, this repository will guide you in preparing data, building models, and gaining actionable insights 
from trading patterns.

This repository is a growing resource and will include new notebooks in the future, covering advanced techniques and broader applications of ML in trading. 
It also serves as supplementary material for a series of Medium articles that explain these concepts in detail.

---

## **Table of Contents**
- [About Infotra.io](#about-infotraio)
- [Current Notebooks](#current-notebooks)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)
- [Stay Updated](#stay-updated)

---

## **About Infotra.io**
**Infotra.io** (short for **Informative Trading**) is a web application that combines 
**pattern discovery** with **risk management** to help traders make smarter, 
data-driven decisions. By analyzing candlestick patterns and historical data, 
Infotra.io provides valuable insights into trading opportunities. 
Check it out at [Infotra.io](https://services.infotra.io/).

This repository complements Infotra.io by demonstrating how to:
- Extract labeled data from Infotra.io.
- Prepare and engineer features for ML models.
- Train and evaluate models based on pattern-driven entry predictions with integrated risk management.

---

## **Current Notebooks**
1. **Data Preparation for ML Models `(prepare_labeled_data.ipynb)`**:  
   This notebook guides you through:
   - Loading and cleaning data exported from Infotra.io.
   - Splitting buy and sell opportunities.

2. **Coming Soon**:
   - **Feature engineering**: Create features based on technical indicators and candlestick patterns.
   - **Building ML Models for Trading**: Step-by-step process to train, validate, and interpret models.
---

## **Features**
- Load and clean exported data from Infotra.io.
- Split buy and sell opportunities for focused analysis.
- Perform feature engineering based on candlestick patterns and market indicators.
- Prepare data for ML model training and evaluation.
- Explore additional trading strategies and risk management techniques.

---

## **Getting Started**
### Prerequisites
- **Python 3.7+** installed on your system.
- **Jupyter Notebook** or any compatible IDE for running `.ipynb` files.
- Basic knowledge of trading and machine learning.

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/MaherDeeb/infotra_ml_for_trading.git
   cd infotra_ml_for_trading
    ```
   or for SSH:
    ```bash
    git clone git@github.com:MaherDeeb/infotra_ml_for_trading.git
    cd infotra_ml_for_trading
    ```
2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
3. Run Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
4. Open the desired notebook and start exploring!

## **Usage**
1. Export your candlestick pattern data from **[Infotra.io](https://services.infotra.io/)** as a CSV file. For more info, check [here](https://drive.google.com/file/d/1AZurLnzc0-hKq4rrCYLPT3-L6OWgWLS2/view?usp=sharing).
2. Place the CSV file in the `data/` folder.
3. Open one of the notebooks, such as `prepare_labeled_data.ipynb`, and follow the step-by-step instructions to:
   - Load and clean the data.
   - Split buy and sell opportunities.
   - Have the data ready for feature engineering and model building.

---

## **How It Works**
This repository demonstrates the following key steps:

1. **Data Preparation**: Import and clean exported data from Infotra.io.
2. **Data Splitting**: Separate buy and sell opportunities for specialized analysis.
3. **Feature Engineering**: Add technical indicators and create pattern-driven features.
4. **Model Building**: Train machine learning models to predict trading opportunities.
5. **Performance Evaluation**: Use metrics like accuracy, precision, and recall to assess model effectiveness.

For a detailed explanation of these steps, check out the
related Medium articles: [https://medium.com/me/stories/public].

---

## **Contributing**
We welcome contributions! If you’d like to improve the code, suggest features, or fix bugs:
1. Fork this repository.
2. Create a new branch for your changes.
3. Submit a pull request with a clear explanation of your updates.

---

## **License**
This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and share the code, with proper attribution.

---

## **Stay Updated**
For the latest news, updates, and tutorials, sign up for the **Infotra.io** newsletter. For signing up, please write an email to `newsletter@infotra.io`
Visit [Infotra.io](https://services.infotra.io/) to learn more about data-driven trading.