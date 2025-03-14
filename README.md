To Execute run below command:
python -m streamlit run ai.py

Csv File download here:
https://drive.google.com/file/d/16LvnJSI7on6e4wMec5m_2edSnc4zko8c/view

# AI-vs-Human-text-detection-using-ML
  — In today's digital era, distinguishing between AI-generated text and human-written content has become increasingly important, particularly in academic and  professional domains. This project focuses  developing an advanced machine learning tool designed to accurately identify whether a given text is created by artificial intelligence or written by a human. Using Python programming and cutting-edge natural language processing (NLP) techniques, the project aims to mitigate the potential misuse of AI-generated text. The methodology involves leveraging the GPT-2 model, a sophisticated AI language framework, to calculate the perplexity score of the input text. Perplexity measures the efficiency of a probabilistic model in predicting a text
sample, providing insights into whether the content is likely AI-generated. Additionally, the project incorporates a burstiness analysis, which evaluates word repetition within the text—a common trait of AIgenerated content. To make the tool accessible and userfriendly, the project employs Streamlit to create an interactive web application. This platform allows users to input text and receive instant feedback, including the perplexity score, burstiness score, and a visualization of the most frequently repeated words using Plotly. The application also displays the input text for reference, ensuring a comprehensive and engaging user experience.

I. INTRODUCTION

The AI vs. Human Text Detection Using Machine Learning project addresses the challenge of distinguishing AIgenerated text from human-written content. As AI models create increasingly sophisticated text, this tool leverages Python and advanced natural language processing (NLP) techniques to ensure content authenticity in academic, professional, and creative fields. The tool uses two primary metrics for analysis: perplexity and burstiness. Perplexity, computed using the GPT-2 model, measures how well a model predicts a text sample, indicating the likelihood of AI authorship. Burstiness evaluates word repetition, a trait often seen in AI-generated content. Together, these metrics provide a comprehensive analysis of the input text. Implemented as an interactive web application using Streamlit, the tool allows users to input text or upload documents in formats like PDF, TXT, and DOCX. It provides real-time results, including perplexity and burstiness scores,
along with visualizations of repeated words using Plotly. Preprocessing steps, such as tokenization, stopword removal, and lemmatization, enhance the accuracy of the analysis. For classification, the project integrates machine learning models like Logistic Regression and Support Vector Machines (SVM), trained on diverse datasets. The tool’s modular and scalable design supports various text inputs and ensures accessibility for both technical and non-technical users.Future updates can include additional languages, file formats, and machine learning models, making it a versatile solution for detecting AI-generated text.

II. OBJECTIVES AND METHODOLOGY

The objective of this project is to develop a reliable machine learning-based tool capable of distinguishing AI-generated text from human-written content, ensuring content authenticity and addressing potential misuse in academic, professional, and creative contexts. The methodology focuses on leveraging two core metrics: perplexity, calculated using the GPT-2 model to measure how well a model predicts a text sample, and burstiness, which evaluates word repetition patterns often characteristic of AI-generated content. Text preprocessing steps, including tokenization, removal of stopwords and punctuation, and optional lemmatization or stemming, are applied to clean and standardize the input for accurate analysis. Logistic Regression and Support Vector Machines (SVM) are used for classification, trained on diverse datasets to enhance reliability. The tool is implemented as an interactive web application using Streamlit, allowing users to input text or upload documents in formats like PDF, TXT, and DOCX. It provides real-time analysis, including perplexity and burstiness scores, and visualizes repeated word patterns with Plotly. Designed with scalability and modularity, the tool can handle various text formats and lengths, with provisions for future enhancements like support for additional languages, file formats, and advanced machine learning models.

Research paper Link:
https://journalcrd.org/wp-content/uploads/28-CRD2594.pdf



