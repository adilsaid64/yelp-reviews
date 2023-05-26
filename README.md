# Using Natural Language Processing to Analyze Yelp Reviews

Yelp provides a crowd-sourced review forum for businesses and services. People share their reviews and rate businesses and services. Other users can also rate other people's reviews.

The goal of this project is to build a machine learning model that can predict whether customers are satisfied or not based on the reviews they have written.

My personal learning objective from this project is to explore the basics of Natural Language Processing (NLP), apply feature extraction using Count Vectorizers and understand the theory behind Naive Bayes classifiers.

## Exploratory Data Analysis

**Summary Statistics**

|           | **stars** | **cool** | **useful** | **funny** |
|----------:|----------:|---------:|-----------:|----------:|
| **count** |     10000 |    10000 |      10000 |     10000 |
|  **mean** |      3.78 |     0.88 |       1.41 |      0.70 |
|  **std**  |      1.21 |     2.08 |       2.34 |      1.91 |
|  **min**  |         1 |        0 |          0 |         0 |
|  **25%**  |         3 |        0 |          0 |         0 |
|  **50%**  |         4 |        0 |          1 |         0 |
|  **75%**  |         5 |        1 |          2 |         1 |
|  **max**  |         5 |       77 |         76 |        57 |

**Observations**
- The dataset contains 10000 reviews and 10 features.
- On average the stars given in this dataset is 3.78 and standard deviation around 1.21.


**Thoughts**
- It would be intresting to know how long each review is. How much detail, time and effort do people put into their reviews.

![Alt Text](1.png)
