# Predictive modeling, supervised machine learning, and pattern classification - the big picture


When I was working on my next pattern classification application, I realized that it might be worthwhile to take a step back and look at the big picture of pattern classification in order to put my previous topics into context and to provide and introduction for the future topics that are going to follow.  
Pattern classification and machine learning are very hot topics and used in almost every modern application: Optical Character Recognition (OCR) in the post office, spam filtering in our email clients, barcode scanners in the supermarket ... the list is endless.  
In this article, I want to give a quick overview about the main concepts of a typical supervised learning task as a primer for future articles and implementations of various learning algorithms and applications.


<a class="mk-toclify" id="table-of-contents"></a>

### Table of Contents

- [Machine Learning and pattern classification](#machine-learning-and-pattern-classification)
- [Supervised, unsupervised, and reinforcement learning](#supervised-unsupervised-and-reinforcement-learning)
- [Supervised learning - a typical workflow](#supervised-learning-a-typical-workflow)
    - [Visualization](#visualization)
    - [Workflow diagram](#workflow-diagram)
    - [Raw data collection and feature extraction](#raw-data-collection-and-feature-extraction)
    - [Sampling](#sampling)
    - [Cross-Validation](#cross-validation)
    - [Normalization](#normalization)
    - [Feature Selection and Dimensionality Reduction](#feature-selection-and-dimensionality-reduction)
    - [Learning algorithms and hyperparameter tuning](#learning-algorithms-and-hyperparameter-tuning)
    - [Prediction-error metrics and model selection](#prediction-error-metrics-and-model-selection)
- [Further Readings](#further-readings)
