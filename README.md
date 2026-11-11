# CS5720 Home Assignment 4

**Student:** Md Shakiful Islam Khan  
**Course:** CS5720 Neural Network and Deep Learning, Fall 2026  
**University:** University of Central Missouri

The [programming notebook](CS5720_Assignment_4_Programming.ipynb) contains the three Part II implementations, comments, and their outputs for the assignment inputs.

## Run in Google Colab

1. Open the notebook file in this repository and use **Download raw file** to save it as an `.ipynb`.
2. Open [Google Colab](https://colab.research.google.com/), choose **Upload notebook**, and select the downloaded file.
3. Choose **Runtime → Run all**. The setup cell installs the required packages and downloads the English stopword list and spaCy model. A CPU runtime is sufficient.

## Programming solutions

| Problem | Implementation and output |
| --- | --- |
| Q1. NLP preprocessing | Uses NLTK to tokenize, filter English stopwords, and apply Porter stemming. Prints the original tokens, the filtered tokens, and the stems. |
| Q2. Named entity recognition | Uses spaCy's English model to print each detected entity, its predicted label, and its zero-based start and end offsets. The end offset is exclusive. |
| Q3. Scaled dot-product attention | Uses NumPy to calculate scaled scores, apply row-wise softmax, and multiply the weights by the value matrix. Prints both result matrices. |
