# Drug Review Recommender System

Welcome to the Drug Review Recommender System model! This system uses drug review data to help users find relevant information about medications and make informed decisions about their healthcare.

## Table of Contents

1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
3. [Usage](#usage)
4. [Data](#data)
5. [Features](#features)


## Introduction

The Drug Review Recommender System is designed to provide personalized drug recommendations based on user preferences and historical drug review data. Whether you're a patient looking for information on a specific medication or a healthcare professional seeking insights on drug effectiveness, this system can help you make more informed choices.

## Getting Started

### Prerequisites

Before using this recommender system, make sure you have the following dependencies installed:

- Python (>= 3.6)
- Pandas
- NumPy
- Scikit-learn
- Google Colab

### Installation

git clone https://github.com/mamudou1/Recommender_system_using_drug_review.git

Install the required Python packages:


## Data

The Drug Review Recommender System uses drug review data, typically consisting of the following attributes:

- `drugName`: The name of the drug being reviewed.
- `condition`: The medical condition for which the drug was prescribed.
- `review`: The text of the patient's review of the drug.
- `rating`: The patient's rating of the drug.
- `date`: The date the review was submitted.

 datasets is availabe at (https://www.kaggle.com/datasets/jessicali9530/kuc-hackathon-winter-2018).

## Features

- **Personalized Recommendations:** The system tailors drug recommendations to individual users based on their preferences and historical reviews.


- **Flexible Recommendation Algorithms:** You can choose from various recommendation algorithms to suit your specific needs, whether collaborative filtering, content-based filtering, or hybrid approaches.

## Recommendation Algorithms

The Drug Review Recommender System offers the following recommendation algorithms:

1. **Collaborative Filtering:** This algorithm identifies similar users and recommends drugs that have been highly rated by those users.

2. **Content-Based Filtering:** This algorithm recommends drugs based on their attributes (e.g., drug name, condition, and review text) and user preferences.

3. **Hybrid Filtering:** A combination of collaborative and content-based filtering, providing a balanced approach to drug recommendations.




**Disclaimer:** This system is for educational and informational purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment. Always seek the advice of your physician or other qualified healthcare providers with any questions you may have regarding a medical condition or treatment.