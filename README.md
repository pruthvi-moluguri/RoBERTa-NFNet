1) Introducing a novel multi-modal multi-label classification model, RoBERTa-NFNet, is a softmax-weighted fusion of Transformer-based RoBERTa and NFNet Convolutional Neural Network, which integrates both the Chest X-rays and associated reports.
2) Effective extraction of features from both written reports and CXRs using RoBERTa as the language encoder and NFNet as the vision encoder.
3) A fusion mechanism that combines features from both modalities using a softmax-weighted feature fusion and a mixed encoder, enabling the model to take use of complimentary information.
4) Achieved significant performance gains, reaching 98.31% AUC and 92.11% F1-score, surpassing existing baseline models in multi-label classification tasks. 
