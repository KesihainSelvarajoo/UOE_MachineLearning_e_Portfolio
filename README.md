# UOE Machine Learning e-Portfolio

**Student:** Kesihain Selvarajoo  
**Module:** Machine Learning  
**Submission:** Final Assessment / e-Portfolio  
**Branch:** `feat/submission`

This repository contains my Machine Learning e-Portfolio submission. It collates evidence of practical work, analytical reporting, model development, reflection, and professional learning across Units 1–12 of the module.

The portfolio demonstrates progression from exploratory data analysis and classical machine learning into clustering, neural networks, convolutional neural networks, model performance evaluation, and future-facing machine learning considerations.

---

## 1. Portfolio Purpose

The purpose of this e-Portfolio is to evidence my learning and development across the module. It includes:

- Practical notebooks and datasets used during weekly activities.
- Analytical and project reports.
- Final deep learning presentation material.
- Reflective artefacts linked to legal, social, ethical and professional issues.
- Evidence of individual contribution, technical development, and critical evaluation.

The portfolio is structured by unit so that the marker can clearly follow the development of skills and knowledge over the duration of the module.

---

## 2. Repository Structure

```text
.
├── README.md
├── AirbnbAnalysis.ipynb
├── CIFAR10_Track2_CNN_Object_Recognition.ipynb
├── final-assessment/
│   └── Machine_Learning_Final_Assessment_ePortfolio_Report.docx
│
├── unit01-industry-4-5/
│   └── retrospective-initial-post.md
│
├── unit02-eda/
│   ├── Unit02_A_Tutorial_on_Exploratory_Data_Analysis.ipynb
│   ├── Unit02_auto_mpg.csv
│   ├── Unit02_train.csv
│   └── Unit02_test.csv
│
├── unit03-regression-correlation/
│   ├── Unit03_Ex1_covariance_pearson_correlation.ipynb
│   ├── Unit03_Ex2_linear_regression.ipynb
│   ├── Unit03_Ex3_multiple_linear_regression.ipynb
│   └── Unit03_Ex4_polynomial_regression.ipynb
│
├── unit04-linear-regression/
│   ├── Unit04_demo_correlation_regression_fuel_consumption.ipynb
│   ├── Unit04_FuelConsumption.csv
│   ├── Unit04_Global_GDP.csv
│   └── Unit04_Global_Population.csv
│
├── unit05-similarity/
│   └── jaccard-coefficient-calculation.md
│
├── unit06-kmeans-airbnb/
│   ├── Analytical_Report.docx
│   ├── Airbnb_Business_Report.docx
│   └── AirbnbAnalysis.ipynb
│
├── unit07-perceptron-mlp/
│   ├── Unit07_Ex1_simple_perceptron.ipynb
│   ├── Unit07_Ex2_perceptron_AND_operator.ipynb
│   └── Unit07_Ex3_multi_layer_perceptron.ipynb
│
├── unit08-gradient-descent/
│   └── Unit08_Ex4_gradient_descent_cost_function.ipynb
│
├── unit09-11-cnn-performance/
│   ├── CIFAR10_Track2_CNN_Object_Recognition.ipynb
│   ├── CIFAR10_Track2_CNN_Object_Recognition_Colab.pdf
│   ├── Deep_Learning_Summative_Presentation.pdf
│   ├── Summative_Presentation_Transcript.docx
│   └── Unit11_model_Performance_Measurement.ipynb
│
└── unit12-future-ml/
    └── future-of-machine-learning-reflection.md
```

> Note: File names may differ slightly depending on the final upload, but the unit-level folder structure should be retained for clarity.

---

## 3. Unit-by-Unit Evidence Summary

| Unit | Main Evidence | Learning Focus |
|---|---|---|
| Unit 1 | Retrospective initial post on Industry 4.0/5.0 and information system failure | Legal, social, ethical and professional issues |
| Unit 2 | Auto-mpg EDA notebook and datasets | Missing values, skewness, kurtosis, correlation, visualisation and encoding |
| Unit 3 | Correlation and regression notebooks | Covariance, Pearson correlation, linear, multiple and polynomial regression |
| Unit 4 | Fuel consumption and Global Population/GDP regression activities | Regression using real-world datasets |
| Unit 5 | Jaccard coefficient calculation | Similarity measurement |
| Unit 6 | Airbnb analytical report and K-means analysis | Unsupervised learning, segmentation and business interpretation |
| Unit 7 | Perceptron and multi-layer perceptron notebooks | Neural network foundations |
| Unit 8 | Gradient descent notebook | Optimisation, learning rate and cost reduction |
| Unit 9 | CNN object recognition activity | CNN application and ethical/social reflection |
| Unit 10 | CNN continuation and image recognition evidence | Feature learning and data distribution |
| Unit 11 | CIFAR-10 CNN project, presentation and transcript | Model performance measurement and critical appraisal |
| Unit 12 | Future of ML reflection | Self-supervised learning, NAS, Edge AI, ethics, scalability and sustainability |

---

## 4. Major Project Evidence

### Unit 6: Airbnb Analytical Report

The Unit 6 work focused on Airbnb New York City listing data. The project used exploratory analysis and K-means clustering to identify meaningful listing segments based on price, availability, review activity and host scale.

Key learning points:

- K-means clustering can support business segmentation.
- Standardisation is important for distance-based algorithms.
- Dataset limitations must be acknowledged before making business claims.
- Review activity can be used only as an imperfect proxy for demand when booking and revenue data are unavailable.

### Unit 11: CIFAR-10 CNN Object Recognition Project

The final project focused on object recognition using the CIFAR-10 dataset. A baseline CNN was compared with an improved CNN using data augmentation, batch normalisation, dropout, early stopping and learning-rate scheduling.

Key result summary:

| Metric | Baseline CNN | Improved CNN |
|---|---:|---:|
| Test accuracy | 74.26% | 82.51% |
| Final validation accuracy | 73.72% | 82.33% |
| Test loss | 0.9621 | 0.5152 |
| Macro F1-score | - | 82.26% |

Key learning points:

- High training accuracy alone does not prove good model performance.
- Validation and test performance are more important indicators of generalisation.
- Data augmentation and regularisation helped reduce overfitting.
- Class-level metrics and confusion matrix analysis are necessary to understand model weaknesses.

---

## 5. Reflection and Professional Development

The final report includes a reflective section structured around the module journey and professional learning. It covers:

- Knowledge development across different machine learning algorithms.
- My individual contributions to analytical and model-development activities.
- Experience of taking ownership of work in a development-team style.
- Professional and personal development, including improved planning, prioritisation and work ethic.

A key learning from this module is that machine learning should not be treated as isolated model execution. It requires disciplined data preparation, suitable algorithm selection, critical performance evaluation, ethical awareness and clear communication of limitations.

---

## 6. How to Review This Portfolio

Recommended review order:

1. Start with `final-assessment/Machine_Learning_Final_Assessment_ePortfolio_Report.docx`.
2. Review the unit folders in sequence from Unit 1 to Unit 12.
3. Pay particular attention to:
   - `unit06-kmeans-airbnb/`
   - `unit09-11-cnn-performance/`
   - `unit12-future-ml/`
4. Use the final assessment report as the guide that explains how each artefact contributes to the learning outcomes.

---

## 7. Academic Integrity Statement

All artefacts in this repository are submitted as evidence of my learning and development during the Machine Learning module. Where external datasets, documentation or academic sources were used, they are referenced in the final assessment report. The portfolio is intended to provide a transparent evidence trail of the work completed, the methods applied and the lessons learned.

---

## 8. References

The full Harvard-style reference list is included in the final assessment report. Key sources include:

- Breiman (2001) on Random Forests.
- MacQueen (1967) on K-means clustering.
- Krizhevsky, Nair and Hinton (2009) on the CIFAR-10 dataset.
- TensorFlow and Keras documentation for CNN implementation.
- scikit-learn documentation for KMeans and model implementation.
- Rolfe, Freshwater and Jasper (2001) for reflective practice.
