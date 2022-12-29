# introducution-to-language-models
- This repository is an introduction of autoregressive character level language models for creating names.
- A total of 32033 names is used to train models defined available at: https://raw.githubusercontent.com/karpathy/makemore/master/names.txt

There are two notebooks used:
## 1. bigram_model
- Aims at defining key concepts of a bigram model and how it can be build
- Introduces a single layer neural network using pytorch

## 2. mlp_model
- Builds a more powerful language model using neural networks with multi-layer perceptrons
- Introduces key concepts in  multi-layer perceptrons


## Python
All models are built using Python. Specifically using the following packages,
- Matplotlib
- Pytorch

### Python setup for local environment
1. If not installed download and install python 3.7 or greater 
2. If not installed go to terminal and run: ```pip install pipenv```
3. Clone this repo in terminal and cd into it then run:
    1. ```pipenv shell``` 
    2. ```pipenv install```
    3. ```jupyter lab```: This will open a tab that shows localhost:8888 where notebooks can be opened



