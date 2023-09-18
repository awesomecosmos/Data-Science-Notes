# Data Science Notes

This is a repository to store my personal notes about my learnings in Data Science.

## Table of Contents
- [Machine Learning](#machine-learning)
- [Resources](#resources)
- [Tips and Tricks](#tips-and-tricks)

## Machine Learning
- [Evaluation Metrics](#evaluation-metrics)
- [Algorithms](#algorithms)

### Evaluation Metrics

**Classification**
- Accuracy: $accuracy = \frac{TP+TN}{TP+TN+FP+FN}$
- Precision - $precision = \frac{TP}{TP+FP}$
  - High precision = lower FP rate, i.e. not many TP are incorrectly classified as FN
- Recall: $recall = \frac{TP}{TP+FN}$
  - High recall = lower FN rate, i.e. most TP are classified correctly
- F1 Score: $f1 = 2\times \frac{precision\times recall}{precision + recall}$
[(back to Machine Learning)](#machine-learning)
### Algorithms

**KNeighborsClassifier**
- Used for supervised classification
- measured by Accuracy
  
[(back to Machine Learning)](#machine-learning)

## Resources

### R/RStudio

**eBooks**
- https://mastering-shiny.org/
- https://engineering-shiny.org/
- https://happygitwithr.com/

[(back to Resources)](#resources)

## Tips and Tricks
To generate a requirements.txt file from the command line: pip freeze > requirements.txt
