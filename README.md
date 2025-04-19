# SVM Optimization Project

This repository contains a Jupyter notebook implementing SVM optimization on the UCI Wine Quality dataset.

## Assignment Requirements
- Selected multi-class dataset from UCI library with rows between 5k and 30k
- Split dataset 70/30 for training and testing
- Created 10 different samples from training data
- Optimized SVM for each sample using 100 iterations
- Recorded best accuracy and parameters for each sample
- Generated convergence graph for best-performing sample

## Dataset
- UCI Wine Quality (White Wine)
- 4,898 samples, 11 features + 1 target variable (quality)
- Multi-class classification problem (quality scores 3-9)

## Results

### Comparative Performance Table
The table below shows the performance comparison of optimized SVM across the 10 different samples:

<img src="https://github.com/ayu-shiirathore/Topsis-for-pretrained-models-of-text-generation/blob/main/Screenshot%202025-02-02%20212220.png" alt="Sample Image" />

### Convergence Graph
The convergence graph for the best-performing SVM model:

<img src="https://github.com/ayu-shiirathore/Topsis-for-pretrained-models-of-text-generation/blob/main/Screenshot%202025-02-02%20212220.png" alt="Sample Image" />


## Implementation Details
The implementation includes:
- Data preprocessing and standardization
- SVM parameter optimization using GridSearchCV
- Performance evaluation with accuracy metrics
- Visualization of results and model convergence


