# Aayat-Azad-CODE-1
Create practical 1
This workflow focuses on predicting the category of an item based on its features. Here is the step-by-step breakdown of how the logic works:
1. The Dataset
The Iris (flowers) or Wine (chemical profiles) datasets are standard benchmarks. They consist of:
Features (X): Measurements like petal length or alcohol content.
Target (y): The specific class or label (e.g., Setosa vs. Versicolor).
2. Train-Test Split
Before training, we split the data (usually 80/20 or 70/30).
Training Set: Used to teach the model.
Testing Set: Kept hidden from the model to act as a "final exam" to see how it handles data it has never seen before. This prevents overfitting (memorization).
3. Model Training
Logistic Regression: Despite its name, it’s used for classification. It calculates the probability that an input belongs to a certain category using a sigmoid function.
Decision Tree: Uses a flowchart-like structure. It asks a series of "Yes/No" questions about the features (e.g., "Is petal width > 0.8?") to narrow down the correct class.
4. Evaluation Metrics
Accuracy: The simplest metric—it’s the percentage of correct predictions out of the total. While useful, it can be misleading if one class is much more common than others.
