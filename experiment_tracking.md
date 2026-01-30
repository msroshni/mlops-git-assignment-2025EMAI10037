## Manual Experiment Tracking Table
| Experiment ID | Model Type | Hyperparameters | Preprocessing Steps | Feature Selection | Train/Test Split | Precision | AUCScore |
|---------------|------------|-----------------|---------------------|-------------------|------------------|-----------|----------|
|    EXP-01     |DecisionTree|      Default    |   cleaned, encoded  |    All features   |       80/20      |    79.7   |    80.4  |
|    EXP-02     |DecisionTree|  Max depth = 6  |   cleaned, encoded  |    All features   |       80/20      |    79.5   |    79.2  |
|    EXP-03     |DecisionTree|      Default    |   cleaned, encoded  |    Numeric only   |       75/25      |    78.9   |    79.4  |
|    EXP-04     |DecisionTree|      Default    |   cleaned, encoded  |    All features   |       80/20      |    79.7   |    80.4  |