# SkimLit

A text classification model that skims through literature and makes it readble.

Purpose - To make medical docs/abstracts/literature easy to readble

The model is trained on PubMed abstracts and is a replication of model used in https://arxiv.org/pdf/1612.05251.pdf

Build using numpy,pandas,Tensorflow and spacy

Can be deployed/used in a user-friendly environmeng using gradio.

The notebook covers multiple models using NaiveBayes,token embeddings,char embeddings ,combination of both,positional embedding along with previous techniques.

Refer screenshots for working.
## Screenshots

![App Screenshot](https://github.com/aryan1519/RandomStuff/blob/main/step1.png)

![App Screenshot](https://github.com/aryan1519/RandomStuff/blob/main/step2.png)

![App Screenshot](https://github.com/aryan1519/RandomStuff/blob/main/step3.png)


TO DO

* While displaying positions of the labels can be adjusted (Eg conclusion,results in the end objective,etc in the beginning).

* Trained only for 3 epochs. Can be trained for longer with callbacks.

* The model can be fine tuned to get better results.

* Feature Engineering may help in improvement (line numbers and total lines in abstract can be used differently).

* USE is used instead of GloVe(used in paper). Results can be compared.

* Replacing USE with BERT PubMed expert (pretrained on PubMed texts) may improve results. 
