# BE-Semantic-PDS
Semantic Plagiarism Detection System for English Texts

CODE folder:
dataloader.py - loads data from the training MSRPC 
preprocess.py - preprocessing data in MSRPC
try2.py - BiLSTM for paraphrase detection
finalSimilarity2 - computes final similarity preceded by NER, semantic similarity using LSA, paraphrase detection using BiLSTM
guiTrial2.py - Plagiarism detection GUI
abstract.txt - sample input of self-made corpus containing abstracts from various research papers
sherlock.txt - sample input containing random text data from the Internet
*****

EXECUTION process:
1) Load the data from MSRPC
2) Preprocessing loaded data (tokenization, stop word removal, stemming)
3) Creating a single layer BiLSTM network for paraphrase detection. Vectorization of each pair in MSRPC training set. Concatentation of features given as input to the neural network.
4) For final similarity, do POS Tagging, NER, LSA and Paraphrase detection.
5) Final document similarity report generated shows semantic similarity, whether input is a paraphrase of corpus content, and final plagiarism percentage
6) Report shown in a simple GUI made using tkinter.
*****

Packages installed:
1) PorterStemmer
2) Tensorflow
3) Keras
4) ScikitLearn TfidfVectorizer
5) ScikitLearn TruncatedSVD
6) NLTK Word Tokenizer
7) StanfordNERTagger
8) Gensim Doc2Vec
*****
*****
