# AKSHITMEHTA_groupIV
Machine Learning (ML) is the process of training a software model on data to make predictions or generate content (like text, images, audio, or video).
instead of using complex hand-written code or hardcoded mathematical formulas (e.g., fluid dynamics equations for weather forecasting), ML algorithms learn underlying mathematical patterns directly from large datasets.
supervised learning: Models learn from labeled training data containing input-output pairs (known as features and label).
Regression: Predicts continuous numerical values (e.g., housing prices or travel times).
Classification: Predicts discrete categories. It can be binary (e.g., spam/not spam) or multiclass (e.g., predicting rain, snow, or hail).
Unsupervised Learning: Identifies hidden patterns or groupings in unlabeled datasets without human-provided answers. A primary technique is clustering (e.g., grouping weather patterns automatically).
Reinforcement Learning: Models discover an optimal strategy or policy through trial and error by receiving rewards or penalties within an environment (e.g., training robots or game-playing models like AlphaGo).
Generative AI: Models designed to generate brand-new content based on prompt inputs across multiple formats (such as text-to-text, text-to-image, text-to-code, or image-to-text). They typically rely on initial unsupervised learning to mimic patterns, followed by fine-tuning with supervised or reinforcement learning
Features: The input variables used to make predictions (e.g., temperature, humidity).
Label: The target "answer" or value the model aims to predict (e.g., rainfall amount).
Labeled Examples: Data containing both features and the correct label. Unlabeled examples contain only features.
dataset Quality: Effective datasets must be both large (sufficient number of examples) and highly diverse (covers a wide range of conditions) to ensure accurate predictions. Adding more relevant features can also improve predictive power.
Model: The mathematical representation that links feature patterns to label outputs.
Training: The iterative process where the model processes labeled data, compares its predictions to actual values, calculates the loss (difference between predicted and actual values), and updates its parameters to minimize error.
Evaluating: Testing the trained model on a dataset using only features to compare its predictions against true labels before real-world deployment.
Inference: Using the trained and validated model to make predictions on new, unlabeled data.
Unsupervised Learning: A machine learning technique that uses algorithms to analyze and cluster unlabeled datasets, discovering hidden patterns or groupings without human intervention or pre-existing labels
Primary applications include exploratory data analysis, customer segmentation, recommendation engines, cross-selling strategies, image recognition, and medical imaging.
Clustering: Groups unlabeled data based on similarities or differences.
Exclusive ("Hard"): Each data point belongs strictly to one cluster (e.g., K-means clustering).
Overlapping ("Soft"): Data points can belong to multiple clusters with degrees of membership (e.g., Fuzzy K-means).
Hierarchical (HCA): Organizes clusters into tree-like structures using agglomerative (bottom-up merging) or divisive (top-down splitting) methods visualized via dendrograms.
Probabilistic: Clusters data based on probability distributions, such as Gaussian Mixture Models (GMM).
Association Rules: Identifies relationships between variables in transactional datasets
Dimensionality Reduction: Compresses datasets with high feature counts while preserving essential structure to prevent overfitting and speed up processing.
Principal Component Analysis (PCA): Uses linear transformations to extract uncorrelated orthogonal directions with maximum variance.
Singular Value Decomposition (SVD): Factorizes a matrix to reduce noise and compress data (e.g., image files).
Autoencoders: Uses neural networks with an encoding bottleneck layer to compress data and a decoding layer to reconstruct it.
