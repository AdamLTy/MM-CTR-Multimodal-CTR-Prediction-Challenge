# MM-CTR-Multimodal-CTR-Prediction-Challenge
## 1.Qwen2.5-vl-7B to get emb
using the second-to-last hidden layer with mean pooling to obtain embeddings
## 2.Using PCA to reduce the dimensionality of embeddings
## 3.Using the default settings of the DIN recommendation model
Hyperparameter scheme:  
embedding_regularizer: 0  
net_regularizer: 0  
net_dropout: 0.11  
learning_rate: 2.e-3  
batch_size: 7168  
