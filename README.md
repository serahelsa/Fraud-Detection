
# ROS Sampling and LIME Interpretability for E-commerce Fraud Detection

This project investigates the effects of sampling on imbalanced data for fraud detection, and the reliability of LIME interpretations for models used in fraud detection.
The models considered for the study are:

- Decision tree
- Random Forest
- Logistic Regression
- Artificial Neural Network

The project aimed to investigate the impact of the ROS (Random Oversampling) sampling approach on imbalanced data for fraud detection, as well as the reliability and stability of LIME (Local Interpretable Model-Agnostic Explanations) interpretations of the models. The study concluded that ROS significantly improved the performance of the models and that accuracy is not an appropriate measure for evaluating the performance of imbalanced classification. The study found that ROC-AUC, precision, recall, and F1-score are more reliable performance measures. The analysis of LIME interpretations suggested that they are not always stable and reliable and that feature importance and LIME interpretation may not always align with the weighted features.

The input files required for this project are:

- `train_transaction.csv`:Transaction file has features engineered by Vesta and associated with online transactions.
- `train_identity.csv`: Identity file contains identity information like DeviceType,network connection information, and digital signature.


## Libraries Used

The following Python libraries were used in this project:

- numpy
- pandas
- matplotlib
- seaborn
- datetime
- sklearn
- tensorflow

## Usage

1. Clone the repository to your local machine:

   git clone https://github.com/serahelsa/Fraud-Detection.git

2. Open the Jupyter notebook file `Fraud_Detection_ROS.ipynb` in Jupyter notebook.

3. Run the notebook cells in sequence to reproduce the analysis.

4. Performance of Fraud Detection Models is displayed at the end of the notebook.


