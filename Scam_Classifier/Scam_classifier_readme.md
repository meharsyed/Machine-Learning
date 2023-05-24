Its a Scam(fraud) classifier Project in which we have different types of datasets to integrate and then classify a specific message or an email as a fraud(scam) or real message.
The Datsets are firest pre-processed and then integrated to form a single file contaning nearly 40000 instances(observations) and their corresponsing labels. The text input columns
are first preprocessed and then passed from a pipeline to get the embedding and tokenizations of the input text features before passing them to the input model for training process. 

The preprocessed Dataset is then splitted into train, validation and testing datasets with 70/10/20 ratio. (Keep in mind the Class balance splitting of the dataset).

A pretrained Transformer named as **BERT**( (Bidirectional Encoder Representations from Transformers) is a popular natural language processing (NLP) model, is used to train the model and 
it can classify the preprocessed splittied training dataset into Real/ Fake classes. 

Model is evaluated on the testing dataset as well as the unseen dataset to visualize the model performance in the form of confusion matric and heatmap. 

The main code .pyfile and notebook both are uploaded in this reository.
