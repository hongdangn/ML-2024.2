# ML-2024.2
This project is a course project for Introduction to Machine learning and Data mining- IT3190 at HUST.

# Overview 

Movies are a popular form of entertainment today, but choosing a good one can be challenging. Many people rely on others' opinions, yet reading long reviews to get a sense of the overall experience can be painfully dull. A quick, clear summary or rating system would make it easier to decide what’s worth watching without wasting time.

Sentiment analysis offers a smart solution to this problem. In this project, *Sentiment Analysis with Reviews from Rotten Tomatoes*, we use Machine Learning and Deep Learning techniques to automatically determine whether a review is positive or negative. This helps users quickly understand the general opinion about a movie without reading through lengthy reviews.

In this project, we use the Stanford Sentiment Treebank 2 (SST-2), a well-known dataset in natural language processing developed by Socher et al. at Stanford University. SST-2 contains short English sentences extracted from Rotten Tomatoes movie reviews, each labeled as either positive or negative. With around 67,000 training samples and 872 test samples, this dataset is ideal for binary sentiment classification tasks and serves as a strong benchmark for evaluating sentiment analysis models.

Building on the SST-2 dataset, we enhance our model by applying various data augmentation techniques to expand and diversify the training data. This helps improve model robustness and generalization. In the main phase of our work, we use word vectorization methods to convert text into numerical representations, then evaluate the performance of several Machine Learning and Deep Learning algorithms to identify the most effective approach for sentiment classification.

For more detail of Standford Sentiment Treebank 2, you can find it here: [SST-2](https://paperswithcode.com/dataset/sst?fbclid=IwZXh0bgNhZW0CMTEAAR5xhREFkNT5VU10KKZBuOWIqSDdl4idKX-wnyt9MoDbPYuCEY_eRFi_pB3Z6w_aem_Arnobghj8aX-sn4PtM9eaA)

# Directories:
- [data](https://github.com/hongdangn/ML-2024.2/tree/main/data): All datasets including augmented dataset
- [src](https://github.com/hongdangn/ML-2024.2/tree/main/src): Source code, implemented by Scikit-learn & Pytorch
  - [src/preprocess](https://github.com/hongdangn/ML-2024.2/tree/main/src/preprocess): Code for preprocessing phase
  - [src/dl](https://github.com/hongdangn/ML-2024.2/tree/main/src/dl): Code for Deep Learning benchmarks (ANN, RNN, LSTM, Ensembler)
  - [src/ml](https://github.com/hongdangn/ML-2024.2/tree/main/src/ml): Code for Machine Learning benchmarks (KNN, SVM, Logistic regression, Naive Bayes, Decision tree, Random forest)

# Collaborators

| Name                     | Student ID | Email                                        |
|--------------------------|------------|----------------------------------------------|
| Nguyen Hong Dang         | 20220025   | [dang.nh220025@sis.hust.edu.vn](mailto:dang.nh220025@sis.hust.edu.vn)       |
| Ngo Duy Anh              | 20220069   | [anh.nd220069@sis.hust.edu.vn](mailto:anh.nd220069@sis.hust.edu.vn)       |
| Phung Cong Hieu           | 20224848   | [hieu.pc224848@sis.hust.edu.vn](mailto:hieu.pc224848@sis.hust.edu.vn)      |
| Nguyen Hoang Xuan Son     | 20224896   | [son.nhx224896@sis.hust.edu.vn](mailto:son.nhx224896@sis.hust.edu.vn)      |
