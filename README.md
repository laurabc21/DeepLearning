# Deep Learning Project: Sentiment Analysis for Mental Health
In this project, I implement DistilBERT for a 7-label classification task using the Sentiment Analysis for Mental Health dataset from Kaggle (https://www.kaggle.com/datasets/suchintikasarkar/sentiment-analysis-for-mental-health). The dataset focuses on sentiment classification in the context of mental health discussions.

Class Distribution Strategies: To improve model performance, I explore different approaches to handling class imbalances and conduct multiple experiments:

1. Stratified Sampling: Ensuring that each class is proportionally represented in both training and validation sets.
2. Class Balancing (Training Set Only): Adjusting the class distribution only within the training data to prevent any single class from dominating learning.

Hyperparameter Tuning Experiments: Beyond handling class imbalances, I explore three experiments focusing on:

1. Weight Decay: Regularization to improve generalization.
2. Scheduler Adjustments: Testing different learning rate schedules to optimize model performance.
