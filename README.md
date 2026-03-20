# Magic-Telescope
My focus has been on Supervised Learning, specifically solving a binary classification problem using the MAGIC Gamma Telescope dataset of UCI Machine Learning Repository.

The goal? To distinguish between high-energy Gamma rays (signal) and Hadronic showers (background noise) based on the geometric patterns they leave in the telescope’s camera.

🧠The Conceptual Breakdown:
During this project, I implemented and compared four foundational algorithms:
1) K-Nearest Neighbors (KNN): A "lazy learner" that classifies data points based on how close they are to their neighbors in the feature space.
2) Logistic Regression: A linear model that uses a sigmoid function to map probabilities between 0 and 1.
3) Naive Bayes: Based on Bayes’ Theorem, it assumes all features are independent (hence "naive") to calculate the probability of a class.
4) Support Vector Machine (SVM): This looks for the "Optimal Hyperplane"—the boundary that maximizes the margin between the two classes.

🏆 Why SVM Performed Best
After evaluating Accuracy, Precision, and Recall, Support Vector Machine (SVM) was the clear winner. Here’s why it excelled:
~Optimal Margin: It doesn't just separate data; it maximizes the "gap" between classes for better reliability.
~High-Dimensional Precision: It excels at processing the 10+ geometric attributes of telescope data simultaneously.
~Non-Linear Power: The "Kernel Trick" allows it to find complex boundaries that linear models simply can't see.

