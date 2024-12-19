# DATA-ANALYTICS-NSSC-24-Cosmic-Collision-
The "Cosmic Collision" project analyzes asteroid risks to Earth using a dataset of asteroid features. By employing data analytics and machine learning, it classifies asteroids as hazardous or non-hazardous. The project includes exploratory data analysis, feature engineering, and predictive modeling to enhance planetary defense efforts.
# Cosmic Collision - Analyzing Asteroid Risks with Data

## Overview

Asteroids are small, rocky objects that orbit the Sun, primarily found in the region between Mars and Jupiter known as the asteroid belt. They are remnants from the early solar system, formed over 4.6 billion years ago, and are considered planetesimals, or building blocks of planets that never coalesced into a larger body due to gravitational disturbances, particularly from Jupiter. Asteroid impacts have been a constant force shaping Earth's history. From minor events that leave barely a trace to catastrophic collisions that have caused mass extinctions, these cosmic encounters have played a significant role in our planet's evolution. Given the potential for devastating consequences, scientists worldwide are dedicated to detecting and tracking the asteroid impact threat. To mitigate this risk, it is crucial to identify and analyze asteroids that could pose a hazard.

### Objective of the Analysis: Data-Driven Classification of Hazardous Asteroids

The primary objective of this analysis is to use data analytics and machine learning techniques to determine the likelihood of an asteroid being hazardous to Earth based on various features provided in the dataset. This includes examining characteristics such as the asteroid's size, orbital parameters, velocity, and proximity to Earth's orbit.

By analyzing these features, the goal is to develop predictive models that classify asteroids into hazardous and non-hazardous categories. This classification is crucial for prioritizing which asteroids require further monitoring, potential deflection efforts, or other mitigation strategies. We will also identify asteroids exhibiting unusual or anomalous behavior that may warrant closer attention.

## Dataset

The dataset used for this analysis can be found [here](#). The description of the features used is provided [here](#).

## Problem Statement

### 1. Exploratory Data Analysis (EDA) (20 points)

#### 1.1 Data Inspection (7 points)
- Inspect the dataset and determine the data types of all features (numerical, categorical).
- Calculate and analyze basic statistics for each numerical feature.
- Identify features that have missing values.
- Identify the numerical and categorical features of the dataset.
- Use imputation to fill the null values in the dataset.

#### 1.2 Statistical Inference (6 points)
- Plot the distribution of numerical features to assess the skewness of the data.
- Identify potential outliers in the numerical columns.
- Explore the relationship between different features using scatter plots or correlation matrices.

#### 1.3 Visualization (4 points)
- Create a pairplot using Seaborn to visualize relationships between multiple numerical features simultaneously.
- Discuss the insights gained from the pairplot.

#### 1.4 Tackling Class Imbalance (3 points)
- Analyze class imbalance in the dataset and propose methods to tackle it.

### 2. Numerical Interpretation and Mathematical Analysis (20 points)

#### 2.1 Feature Engineering (15 points)
- Combine date features into a single feature.
- Calculate various orbital parameters and distances.
- Create additional features for improving accuracy.

#### 2.2 Additional Features (5 points)
- Create innovative features based on your understanding of the problem.

### 3. Handling Binned Values (5 points)
- Modify binned features with ordinal relationships.
- One-hot encode non-ordinal binned features.

### 4. Hazardous Classification (35 points)
- Build a classifier to classify asteroids as Hazardous or Not Hazardous.
- Implement K-Fold Cross Validation and optimize hyperparameters.
- Plot performance metrics such as ROC curve and Confusion Matrix.

### 5. Anomaly Detection (20 points)
- Perform anomaly detection using both an inbuilt library and a custom algorithm.
- Compare results from both methods.

## Description of the Features of Asteroid Impact Dataset

- **Epoch Date Close Approach**: The specific date when the asteroid is closest to Earth during its orbit.
- **Relative Velocity (km per sec)**: The speed at which the asteroid is moving relative to Earth.
- **Miss Dist. (Astronomical)**: The closest distance between the asteroid and Earth, measured in astronomical units (AU).
- **Semi Major Axis**: The average distance of the asteroid's orbit from the Sun.
- **Hazardous**: A classification indicating whether the asteroid poses a potential threat to Earth based on its orbit and proximity.
- **Diameter**: The size of the asteroid, typically measured in meters or kilometers.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- NASA for providing the data.
- The data science community for their invaluable resources and support.
