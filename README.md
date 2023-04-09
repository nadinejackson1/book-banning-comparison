# Analyzing Censorship: Comparing Nazi Germany to Recent Times in the USA

This project focuses on the analysis and comparison of censorship practices between Nazi Germany and recent times. I am passionate about understanding the historical and contemporary factors driving censorship, and I believe that machine learning techniques can provide valuable insights into the similarities and differences between these time periods. By performing topic modeling and textual analysis, I aim to uncover patterns and trends that can help shed light on the cultural and political forces at play.

### Table of Contents

- Introduction
- Installation
- Usage
- Data Collection and Preparation
- Text Preprocessing
- Topic Modeling using LDA
- Visualizing Topics with Word Clouds
- Comparing Topic Distributions
- Conclusion
- License

### Introduction

Censorship and book banning have been an unfortunate part of human history. Throughout time, governments, institutions, and individuals have attempted to control the dissemination of information and ideas by suppressing certain books or publications. In this project, I analyze and compare censorship practices from two distinct time periods: Nazi Germany and the present day. By leveraging machine learning techniques, such as Latent Dirichlet Allocation (LDA) for topic modeling, I aim to reveal the underlying themes and trends that characterize censorship in both historical and contemporary contexts.
Installation

To run this project, you will need to have Python 3.x installed. Additionally, you will need to install the following libraries:

    pip install pandas
    pip install numpy
    pip install nltk
    pip install scikit-learn
    pip install matplotlib
    pip install wordcloud
    pip install gensim

### Usage

To use this project, simply clone the repository and run the provided Jupyter Notebook (CensorshipAnalysis.ipynb) in a Jupyter environment. Make sure you have the required libraries installed and the dataset files in the appropriate directories.

### Data Collection and Preparation

The data for this project has been gathered from various sources, including historical documents, news articles, and legislative records. These sources provide valuable information about the context and motivations behind censorship practices during Nazi Germany and in recent times. To facilitate the analysis, I have compiled these documents into two separate CSV files: one for Nazi Germany and another for the present day issues in the United States.

### Text Preprocessing

Before conducting any analysis, it is essential to preprocess the text data to ensure that it is suitable for machine learning algorithms. I have performed various preprocessing steps, including:

- Tokenization: Breaking the text into individual words or tokens.
- Lowercasing: Converting all text to lowercase.
- Stopword removal: Eliminating common words that do not carry much meaning, such as "the" or "and".
- Lemmatization: Reducing words to their base or dictionary form, e.g., "running" to "run".

### Topic Modeling using LDA

Latent Dirichlet Allocation (LDA) is a powerful unsupervised machine learning technique for discovering hidden topics in large collections of documents. By applying LDA to the preprocessed text data, I have identified prominent themes in both Nazi Germany and present-day documents. This approach allows for a comparison of the most common topics between the two time periods, shedding light on the similarities and differences in censorship motivations.

### Visualizing Topics with Word Clouds

To better understand and interpret the topics discovered by the LDA model, I have created word clouds for each topic. These visualizations display the most frequently occurring words and bigrams in each topic, providing a clear and concise representation of the themes identified.

### Comparing Topic Distributions

After uncovering the topics within the documents, I have analyzed the distribution of these topics across the two time periods. By examining the prevalence of specific themes in both historical and contemporary contexts, I can draw conclusions about the factors that drive censorship practices.

### Conclusion

Through this project, I have gained valuable insights into the complex and multifaceted world of censorship practices during Nazi Germany and in recent times. By comparing these two periods, I have uncovered intriguing patterns and trends that reveal the cultural, political, and societal factors that influence censorship decisions. This analysis demonstrates the power of machine learning techniques, such as Latent Dirichlet Allocation, in uncovering hidden topics and themes within large collections of documents.

The findings from this project can serve as a foundation for future research, as well as inform discussions and debates surrounding the issue of censorship. By understanding the historical context and contemporary forces at play, we can work towards fostering a more open, diverse, and inclusive society where information and ideas can be freely exchanged.

I am deeply passionate about the power of knowledge, and I believe that understanding the patterns of censorship can help us advocate for a world where every individual has the right to access, share, and engage with diverse perspectives and ideas. By continuing to explore and analyze the factors driving censorship, we can work towards a more informed and enlightened future.

### License

This project is licensed under the MIT License. 
