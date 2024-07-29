# 1 - Fine-tuning DistilBERT

In this notebook, we will demonstrate the process of fine-tuning DistilBERT for sentiment analysis using a dataset of restaurant reviews. DistilBERT is a smaller, faster, and lighter version of BERT (Bidirectional Encoder Representations from Transformers), an encoder-based transformer model introduced by Google in 2018. DistilBERT retains most of BERT's performance while being significantly more efficient, making it a practical choice for many natural language processing (NLP) tasks, including sentiment analysis.

Our goal is to classify each review into positive or negative sentiment categories by leveraging DistilBERT's capabilities. This involves loading the pre-trained DistilBERT model, preparing the dataset, and fine-tuning the model to our specific task.




For further reading on BERT and DistilBERT, refer to the original BERT paper here and the DistilBERT paper [here](https://arxiv.org/abs/1910.01108).



# 2 - Fine-tuning

Fine-tuning DistilBERT involves training the model on our specific dataset to adjust all of its weights, including those in the transformer layers and not just the final classifier layer. This comprehensive update allows the model to better adapt to the nuances of our sentiment analysis task. We use the AdamW optimizer for efficient weight adjustments and train over several epochs, monitoring loss to gauge progress. This method ensures that the model becomes finely tuned to our specific classification challenge, leveraging the full power of DistilBERT's pre-trained knowledge and making it more effective for our dataset.

