
# Skimlit

## Overview

Skimlit is a project designed to enhance the readability and utility of medical abstracts by utilizing Natural Language Processing (NLP) techniques to divide them into four distinct sections: Objective, Method, Background, and Conclusion. This process aims to provide a clearer and more structured view of medical research, making it easier for healthcare professionals and researchers to extract relevant information quickly.

## Objectives

The main objectives of Skimlit are:
- To automate the division of medical abstracts into meaningful sections using NLP.
- To improve the accessibility and interpretability of medical research findings.
- To support researchers and healthcare professionals in quickly identifying the key components of a study.

## Background

Medical abstracts often contain valuable information but can be challenging to parse due to their complex and dense nature. Traditional methods of extracting information involve manual reading and interpretation, which can be time-consuming and prone to human error. Skimlit leverages NLP techniques to automate this process, offering a systematic approach to abstract segmentation.

## Method

Skimlit employs the following NLP techniques to achieve its objectives:

1. **Text Preprocessing**: 
   - Tokenization: Splitting the abstract into sentences and words.
   - Lemmatization: Reducing words to their base or root form.
   - Removal of stop words and punctuation.

2. **Named Entity Recognition (NER)**:
   - Identifying key entities related to medical research such as diseases, treatments, and outcomes.

3. **Text Classification**:
   - Training a classification model to categorize sentences into the four sections: Objective, Method, Background, and Conclusion.

4. **Dependency Parsing**:
   - Analyzing the grammatical structure of sentences to better understand the relationships between words and phrases.

5. **Summarization**:
   - Applying extractive summarization techniques to highlight the most important sentences in each section.

## Results

Skimlit has demonstrated effectiveness in dividing medical abstracts into the specified sections with high accuracy. The results indicate:
- Improved clarity and readability of medical abstracts.
- Faster information retrieval for healthcare professionals.
- Enhanced ability to quickly understand the core components of a study.

## Conclusion

Skimlit represents a significant advancement in the field of medical text processing. By employing advanced NLP techniques, it provides a practical solution for the segmentation of medical abstracts, thereby enhancing their utility and accessibility. Future work will focus on refining the algorithms and expanding the system's capabilities to handle a broader range of medical texts.

## Future Work

- **Algorithm Enhancement**: Improving the accuracy and robustness of the text classification and summarization models.
- **Integration with Medical Databases**: Incorporating Skimlit into existing medical research databases for seamless abstract processing.
- **User Feedback Integration**: Gathering feedback from end-users to refine and enhance the system's performance and usability.


