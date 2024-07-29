# 1 - Fine-tuning DistilBERT

In this notebook, we will demonstrate the process of fine-tuning DistilBERT for sentiment analysis using a dataset of restaurant reviews. DistilBERT is a smaller, faster, and lighter version of BERT (Bidirectional Encoder Representations from Transformers), an encoder-based transformer model introduced by Google in 2018. DistilBERT retains most of BERT's performance while being significantly more efficient, making it a practical choice for many natural language processing (NLP) tasks, including sentiment analysis.

Our goal is to classify each review into positive or negative sentiment categories by leveraging DistilBERT's capabilities. This involves loading the pre-trained DistilBERT model, preparing the dataset, and fine-tuning the model to our specific task.




For further reading on BERT and DistilBERT, refer to the original BERT paper here and the DistilBERT paper [here](https://arxiv.org/abs/1910.01108).
