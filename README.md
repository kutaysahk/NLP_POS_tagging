Sequence Labeling: POS Tagging and Named Entity Recognition
This repository presents a comprehensive comparative study of sequence labeling tasks, specifically focusing on Part-of-Speech (POS) Tagging and Named Entity Recognition (NER). 
The project serves as a technical benchmark, evaluating a wide spectrum of methodologies from classical statistical classifiers to state-of-the-art transformer architectures. 
By implementing these models on standardized datasets, the repository demonstrates the evolution of NLP techniques and their effectiveness in capturing syntactic and semantic linguistic structures.

The research begins with baseline machine learning models, including Naive Bayes, Logistic Regression, and Support Vector Machines (SVM). 
These implementations utilize frequency-based feature extraction such as Count Vectorization and TF-IDF to establish performance standards. 
To address the sequential nature of language, the project incorporates probabilistic graphical models like Hidden Markov Models (HMM) with Viterbi decoding and Conditional Random Fields (CRF). 
These models improve prediction coherence by mathematically accounting for the dependencies between adjacent tags and respecting structural constraints like IOB/BIO formatting.

The study further explores deep learning territory through Convolutional Neural Networks (CNN) and Bidirectional LSTMs (BiLSTM). 
These architectures automate feature engineering, using bidirectional processing to capture both local morphological patterns and long-range global dependencies. 
The pinnacle of the repository is the integration of fine-tuned BERT (Bidirectional Encoder Representations from Transformers) models, which leverage self-attention mechanisms to achieve superior accuracy 
and contextual understanding.

Each component of the repository includes a complete end-to-end pipeline, covering data parsing from CoNLL-U formats, extensive preprocessing for out-of-vocabulary tokens, and rigorous evaluation metrics. 
Through detailed classification reports and confusion matrices, this project provides a clear technical roadmap showing how increasing architectural complexity directly impacts the precision 
and recall of automated grammatical annotation and entity boundary detection.
