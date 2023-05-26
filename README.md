# Using Natural Language Processing to Analyze Yelp Reviews

Yelp provides a crowd-sourced review forum for businesses and services. People share their reviews and rate businesses and services. Other users can also rate other people's reviews.

The goal of this project is to build a machine learning model that can predict whether customers are satisfied or not based on the reviews they have written.

My personal learning objective from this project is to explore the basics of Natural Language Processing (NLP), apply feature extraction using Count Vectorizers and understand the theory behind Naive Bayes classifiers.

## Exploratory Data Analysis

**Summary Statistics**

|           |    **stars** |     **cool** |   **useful** |    **funny** |
|----------:|-------------:|-------------:|-------------:|-------------:|
| **count** | 10000.000000 | 10000.000000 | 10000.000000 | 10000.000000 |
|  **mean** |     3.777500 |     0.876800 |     1.409300 |     0.701300 |
|  **std**  |     1.214636 |     2.067861 |     2.336647 |     1.907942 |
|  **min**  |     1.000000 |     0.000000 |     0.000000 |     0.000000 |
|  **25%**  |     3.000000 |     0.000000 |     0.000000 |     0.000000 |
|  **50%**  |     4.000000 |     0.000000 |     1.000000 |     0.000000 |
|  **75%**  |     5.000000 |     1.000000 |     2.000000 |     1.000000 |
|  **max**  |     5.000000 |    77.000000 |    76.000000 |    57.000000 |

**Observations**
- The dataset contains 10000 reviews and 10 features.
- On average the stars given in this dataset is 3.78 and standard deviation around 1.21.


**Thoughts**
- It would be intresting to know how long each review is. How much detail, time and effort do people put into their reviews.

