# Comparative Analysis of Pre-trained vs. Fine-tuned DistilBERT for Sentiment Analysis

## Introduction
This project aims to critically assess the performance difference between pre-trained and fine-tuned DistilBERT models in the context of multi-class sentiment analysis. Leveraging the robust capabilities of DistilBERT for feature extraction, we embark on a journey to fine-tune this model for enhanced emotion classification from text data, showcasing the significant improvements fine-tuning can achieve in model accuracy.

## Requirements
- Python 3.8+
- PyTorch
- Transformers
- Datasets library
- Scikit-learn
- UMAP-learn
- Matplotlib
- Pandas
- NumPy

## Installation
Set up your project environment with the necessary dependencies by running:

```bash
pip install torch transformers[torch] datasets sklearn umap-learn matplotlib pandas numpy -U
```
## Dataset

* We utilize the "emotion" dataset from Hugging Face's datasets library, featuring text entries tagged with various emotions. This rich dataset serves as the foundation for both training and validating our models, providing a balanced challenge for sentiment analysis.

## Model Training and Evaluation

* The core of our analysis lies in comparing a baseline pre-trained distilbert-base-uncased model against its fine-tuned counterpart. Through the fine-tuning process, we meticulously adjust the model to our specific task, aiming to significantly surpass the baseline accuracy.

## Findings

* Our evaluation presents a detailed comparison, highlighting a 49% increase in accuracy through fine-tuning. These results not only underscore the effectiveness of fine-tuning for specific tasks but also provide valuable insights into the capabilities and adaptability of pre-trained models like DistilBERT in sentiment analysis.

## Conclusion

* This comparative study sheds light on the transformative impact of fine-tuning on pre-trained models. By offering a thorough analysis of performance improvements, our project contributes to a deeper understanding of model optimization techniques in natural language processing.
* For an in-depth exploration of our methodology, model training, and evaluation results, refer to the accompanying Jupyter notebooks and Python scripts.

