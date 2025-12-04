# Feature-Engineering-Using-Snowflake

## What is Feature Engineering ?
- Feature Engineering is the process of selecting, creating or modifying features like input variables or data to help machine learning models learn patterns more effectively.
- It involves transforming raw data into meaningful inputs that improve model accuracy and performance.
- Feature engineering preprocesses raw data into a machine-readable format.
- It optimizes ML model performance by transforming and selecting relevant features.

## Importance of Feature Engineering
- Improve accuracy: Choosing the right features helps the model learn better, leading to more accurate predictions.
- Reduce overfitting: Using fewer, more important features helps the model avoid memorizing the data and perform better on new data.
- Boost interpretability: Well-chosen features make it easier to understand how the model makes its predictions.
- Enhance efficiency: Focusing on key features speeds up the model’s training and prediction process, saving time and resources.

## Feature Engineering techniques
- Feature Creation: It involves generating new features from existing data to highlight hidden patterns.
- Feature Transformation:  It applies mathematical modifications to features to improve model performance or reduce skew. Examples include encoding, log transformation, normalization, and binning.
- Feature Extraction: It reduces data dimensionality by converting raw data into a smaller set of informative features. Techniques include PCA for numerical data and embeddings for text/images.
- Feature Selection: It chooses the most relevant features and removes irrelevant or redundant ones. It improves model accuracy, reduces overfitting, and speeds up training. 
- Feature Scaling: It standardizes the range of independent variables so no feature dominates others. Common methods include Min-Max scaling and Standardization.

## Feature Creation
Feature Creation is the process of generating new, meaningful features from the existing raw data to help machine learning models learn patterns more effectively.
Types of Feature Creation:
- Mathematical Combinations: Creating new features using arithmetic operations.
- Data & Time-driven: Extracting date and time components to improve forecasting or classification.
- Domain-Specific Feature Creation: Using expert knowledge to create meaningful variables.

## Feature Transformation
Feature Transformation is the process of modifying or converting existing features into a format that helps a machine learning model learn patterns more effectively.Transformations improve data quality, reduce skewness, make features comparable, and help algorithms converge faster.
- Normalization & Scaling: Normalization scales each data sample such that its vector length is 1. 
- Standardization: Standardization centers features by subtracting the mean and scales them by dividing by the standard deviation, transforming features to have zero mean and unit variance.
- Encoding: Encoding transforms non-numerical categorical data into numerical forms so ML models can understand them. Types of encoding:
-- Label Encoding: Assigns each category an integer value
-- One-Hot Encoding: Creates a new binary column for each category
-- Ordinal Encoding: Assigns values based on meaningful order
- Mathematical Transformations: These transformations modify the distribution of data to remove skewness or improve linearity. These include Log Transformation, Square-Root Transformation, Binning, etc.






