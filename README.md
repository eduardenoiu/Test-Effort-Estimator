# Test-Effort-Estimator

The training material includes:
- Introduction to Test Effort Estimation: Basics and importance in software development.
- Methodology: Explanation of granularity levels: commits, pull requests, and releases. Data extraction tools: Designite, JavaNCSS, GitHub API. Machine Learning techniques used for prediction.
- Results and Insights: Findings at different granularity levels. Importance of features in predicting test effort.
- Applications: Use cases in industry and academia. Future work.


# Definition: 
Test effort estimation predicts the resources, time, and personnel needed for software testing. This ensures timely project delivery and cost management, improves software quality, reducing maintenance costs and assists in planning and resource allocation.


# Granularity Levels
Commit: A snapshot of changes at the smallest level.
Pull Request: A bundle of commits proposed for integration.
Release: A comprehensive version, ready for deployment.

# Data Extraction Tools
Designite: Extracts architectural metrics and design issues.
JavaNCSS: Provides metrics like non-commenting source statements and cyclomatic complexity.
GitHub API: Retrieves granular data on commits, pull requests, and releases.
TIQVA tool: https://github.com/amuslija/fbd-complexity-tool 

# Machine Learning Techniques
Regression Models: Linear Regression, Lasso, Ridge, Elastic Net.
Classification Models: Random Forests, K-Nearest Neighbors, Support Vector Machines (SVMs), and Multilayer Perceptrons (MLP).
