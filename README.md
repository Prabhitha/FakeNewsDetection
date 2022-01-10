# Fake News Detection using different Machine Learning models

**Word2Vec Vectorizer**

|        Model        |        Hyper Parameter        | Train log-loss | Test log-loss | Train Accuracy | Test Accuracy |
|---------------------|-------------------------------|----------------|---------------|----------------|---------------|
| Logistic Regression |   ElasticNet, alpha = 0.0001  |     0.142      |     0.157     |     94.58%     |     94.35%    |
|      Linear SVM     |     L2 loss, alpha = 0.001    |     0.142      |     0.158     |     94.67%     |     94.52%    |
|         GBDT        | Estimators= 500, Max_depth= 2 |     0.153      |     0.186     |     94.95%     |     93.12%    |
|    Random Forest    | Estimators= 500, Max_depth= 8 |     0.298      |     0.338     |     91.92%     |     89.01%    |
|     Random Model    |               -               |       -        |     0.889     |       -        |       -       |


**TF-IDF Vectorizer**

|        Model        |         Hyper Parameter         | Train log-loss | Test log-loss |
|---------------------|---------------------------------|----------------|---------------|
| Logistic Regression |         L2, alpha = 0.01        |     0.0069     |     0.0283    |
|      Linear SVM     |     ElasticNet, alpha = 0.01    |     0.0159     |     0.0215    |
|         GBDT        |  Estimators= 500, Max_depth= 2  |     0.0022     |     0.0083    |
|    Random Forest    | Estimators= 1000, Max_depth= 10 |     0.2733     |     0.2865    |
|     Random Model    |                -                |       -        |     0.8906    |

