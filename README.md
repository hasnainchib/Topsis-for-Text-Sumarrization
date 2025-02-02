# Topsis-for-Text-Sumarrization
Objective
This project applies the TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution) method to evaluate and rank pre-trained models used for text summarization. The goal is to determine the best-performing model based on key performance metrics.

Approach
Models Considered:

BART
T5
GPT-3
Pegasus
XLNet
Evaluation Metrics:

ROUGE-1, ROUGE-2, ROUGE-L (Higher is better)
Inference Time (Lower is better)
Steps Involved:

Normalization of the decision matrix.
Weight assignment to evaluation metrics.
Calculation of ideal best and worst solutions.
Computation of Euclidean distances and TOPSIS scores.
Ranking of models based on performance.
Results
The output consists of:
A ranked table displaying the models along with their TOPSIS scores.
A bar graph visualizing the TOPSIS scores of the models.
Usage
Run the Python script to obtain rankings of the pre-trained models. Modify the dataset to include additional models or adjust weights based on specific use cases.
