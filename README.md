# Covid-19-BOT
Samantha, A covid-19 information bot which will provide basic information about this pandemic in form of conversation. This bot uses torch based model to train its word bag. 

# Implementation of a Contextual Chatbot in PyTorch.  
Simple chatbot implementation with PyTorch. 


```
### Install PyTorch and dependencies

For Installation of PyTorch see [official website](https://pytorch.org/).

You also need `nltk`:
 ```console
pip install nltk
 ```

If you get an error during the first run, you also need to install `nltk.tokenize.punkt`:
Run this once in your terminal:
 ```console
$ python
>>> import nltk
>>> nltk.download('punkt')
```

## Usage
Run
```console
python train.py
```
This will dump `data.pth` file. And then run
```console
python chat.py
```
## About bot
We made this just to give a basic idea about covid virus and its details. 
we will keep updating this project and next we are trying to make its web interface.
