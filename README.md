Loading Pre-trained BERT: Load a pre-trained BERT model and tokenizer using the transformers library.
Dataset Preparation: Load your dataset, which should contain text and labels. Tokenize the text using BERT tokenizer.
PyTorch Dataset: Create a custom PyTorch dataset class to handle the tokenized inputs and labels.
Fine-tuning BERT: Set up the TrainingArguments and Trainer to fine-tune the BERT model on your dataset.
Embedding Generation: Use SentenceTransformer to generate sentence embeddings for the text data.
Clustering for Topics: Apply KMeans clustering on the embeddings to find topics and assign each text to a cluster.
Displaying Topics: Print out the top phrases for each topic cluster.
Make sure to adjust the dataset paths, column names, and other parameters according to your specific dataset and requirements.
