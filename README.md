# CS334-Final-Project

## Datasets

Extracted from WSD Evaluation Framework: http://lcl.uniroma1.it/wsdeval/

Train: 
Semcor 

Validation:
SE7

Test:
SE2, SE3, SE13, SE15


## Model structure

Words with multiple senses are called polysemes.

Sentences -> Sentence Embeddings (WordPiece) -> Encoder (BERT transformer) -> Features (vectors) of polysemes in sentence
 
Features -> Classifier (MLP neural net) -> Predictions of senses 


## Training the Model
Look at sections 3.1 and 3.2 in the WSD Using BERT paper