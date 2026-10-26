# Daily Learning Log

## Week 1 — Foundations and First ML Model

- **Day 1:** Stock Market Basics, OHLCV, Python, Pandas, Returns, Visualization
- **Day 2:** Pandas Indexing, Date Filtering, Data Cleaning, CSV Persistence
- **Day 3:** Statistics, Cumulative Returns, Volatility, Correlation
- **Day 4:** SMA, EMA, Momentum, RSI, MACD, Bollinger Bands, Feature Engineering
- **Day 5:** Lagged Features, Prediction Targets, Train/Test Split, Baselines
- **Day 6:** Logistic Regression, Feature Scaling, Classification Metrics
- **Day 7:** Week 1 Recap, Pipeline Review, Data Leakage, Model Comparison

## Week 2 — Model Evaluation and Diagnostics

- **Day 1:** Model Evaluation and Error Analysis

- Confusion matrix, true positives/negatives, false positives/negatives
- Accuracy, balanced accuracy, precision, recall, F1 and ROC-AUC
- Baseline vs logistic regression comparison
- Misclassified-date investigation
- Year-by-year test performance
- Error analysis and evaluation limitations

- **Day 2:** Classification Metrics and Class Imbalance

### Day 2 — Classification Metrics and Class Imbalance

- UP/DOWN class distribution
- Accuracy vs balanced accuracy
- Precision, recall and F1
- Macro vs weighted F1
- Class weights in logistic regression
- Standard vs class-weighted model comparison
- Class-specific confusion matrices and prediction rates

**Notebook:** `09_classification_metrics_class_imbalance.ipynb`
- **Day 3:** Probability Calibration and Prediction Thresholds
### Day 3 — Probability Calibration and Thresholds

- Predicted probabilities vs class labels
- Brier score and calibration curves
- Default 0.5 classification threshold
- Validation-based threshold selection
- Precision/recall trade-offs across thresholds
- Separate train, validation and test periods
- Evaluation of the selected threshold on held-out test data


- **Day 4:** Regularization and Feature Analysis

### Day 4 — Regularization and Feature Analysis

- Overfitting, generalization and regularization
- L1 vs L2 penalties and the inverse-strength parameter `C`
- Validation-based regularization comparison
- Training/validation performance gaps
- Feature correlation and redundancy
- Logistic-regression coefficient analysis
- Permutation feature importance
- Final test evaluation after model selection

- **Day 5:** Model Diagnostics and Stability
### Day 5 — Model Diagnostics and Stability

- Walk-forward evaluation with expanding training windows
- TimeSeriesSplit and a one-observation target gap
- Fold-level accuracy, balanced accuracy, F1 and ROC-AUC
- Model stability: mean and standard deviation across folds
- Final held-out test evaluation
- Annual performance diagnostics
- Higher- versus lower-volatility regime analysis

- **Day 6:** Evaluation Improvements

W2 Day 6: reusable evaluation functions, chronological
train/validation/test split, baseline comparison, threshold
selection, final test report, leakage checks.

- **Day 7:** Weekly Review

W2 Day 7: weekly review, reusable evaluation workflow,
feature/target leakage audit, chronological holdout,
baseline comparison, threshold selection, yearly stability,
model-readiness checks.

W3 Day 1: decision tree fundamentals, Gini impurity,
tree visualization, max_depth and min_samples_leaf,
overfitting analysis, validation-based depth selection,
baseline and logistic regression comparison, feature importance.

W3 Day2: Decision tree complexity, max_depth, min_samples_leaf, min_samples_split, overfitting analysis, cost-complexity pruning with ccp_alpha, validation-based hyperparameter selection, final test evaluation, model comparison.

W3 Day3: Random Forest fundamentals, bootstrap sampling, randomized feature selection, ensemble voting, n_estimators/max_features/depth/leaf-size tuning, validation-based model selection, baseline/logistic/tree/forest comparison, confusion matrix, feature importance, out-of-bag evaluation and its time-series limitations.

W3 Day4: Random Forest train-validation diagnostics, baseline and model comparison, overfitting analysis, impurity-based feature importance, permutation importance, and validation-based model selection with final test evaluation.

W3 Day5: Random Forest bootstrap sampling, ensemble voting, out-of-bag evaluation, hyperparameter experiments, validation-based selection, and final test comparison.

W3 Day6: Comparison of majority baseline, logistic regression, decision tree, and Random Forest; training-validation generalization gaps; classification metrics; confusion matrices; and validation-based model selection.

W3 Day7: Review of decision trees, pruning, Random Forest bootstrap sampling, ensemble predictions, OOB limitations, feature importance, generalization gaps, classification metrics, and validation-based model selection.

*Future daily topics will be updated as the project progresses.*
