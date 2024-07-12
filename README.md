# Predicting Chronic Respiratory Diseases Using Socio-Environmental Factors and Geographic Data

This project, which served as my capstone for the Big Data specialization, focuses on investigating and predicting the prevalence of chronic respiratory diseases, specifically asthma and Chronic Obstructive Pulmonary Disease (COPD), based on socio-environmental and geographic factors. The study aims to uncover complex relationships between various environmental, social, and geographical variables and their impact on respiratory health outcomes.

## Phase 1: Data Collection and Analysis

Our research began with an extensive data collection effort, drawing from multiple authoritative sources including the National Health Service (NHS) in England and the Office for National Statistics (ONS). The datasets encompassed a wide range of variables:

- Disease prevalence rates for asthma and COPD
- Quality of care indicators from healthcare providers
- Income levels and socioeconomic status metrics
- Deprivation indices for different geographic areas
- Detailed demographic information
- Geographic variables, including proximity to public parks and private gardens

The data processing phase involved rigorous cleaning, transformation, and integration of these diverse datasets. We employed advanced techniques such as:

- Data merging to combine information from different sources
- Geographic area conversions to ensure consistency across datasets
- Value weighting to account for population differences

These efforts culminated in the creation of a comprehensive panel dataset, serving as the foundation for our in-depth analysis. This dataset allowed us to explore the intricate relationships between socio-environmental factors and the target variables of asthma and COPD prevalence rates at the general practice (GP) level, providing a granular view of health outcomes across different communities.

## Phase 2: Pipeline Development and Predictive Modeling

### Pipeline Construction

We developed a sophisticated data analysis pipeline to ensure consistent and efficient processing of our large dataset. This pipeline included several key components:

1. A feature selection function to identify and focus on the most relevant variables for our specific research questions.
2. Data quality management functions to detect and handle outliers and missing values, crucial for maintaining the integrity and accuracy of our analysis.
3. A time-based filtering function, allowing us to examine trends over specific years or focus on particular time periods of interest.
4. Data normalization procedures to prepare the dataset for machine learning models, ensuring fair comparisons across different scales and units.
5. A function to split the data into training and testing sets, essential for robust model evaluation.
6. Implementation of various machine learning models, enabling us to compare different approaches and identify the most effective predictive techniques.

### Predictive Modeling and Results

Our modeling phase employed a range of machine learning techniques to predict asthma and COPD prevalence:

- Linear Regression: To establish baseline predictions and identify linear relationships between variables.
- Random Forests: Leveraging ensemble methods to capture complex, non-linear interactions between predictors.
- XGBoost: Utilizing gradient boosting to potentially improve predictive accuracy and handle feature interactions.

In total, we ran over 600 different model configurations, systematically exploring various hyperparameters and feature combinations. This extensive modeling effort allowed us to thoroughly assess the predictive power of our socio-environmental and geographic variables in relation to respiratory disease prevalence.

The detailed results of our modeling efforts, including performance metrics, feature importance analyses, and insights into the most influential factors for predicting asthma and COPD prevalence, are comprehensively documented in the project's final report. This report not only presents our findings but also discusses their implications for public health policy and potential areas for future research in the field of respiratory health epidemiology.


