# Unnderstand Neural Networks

This project aims to give clear and progressive explanations about how to use **PyTorch** to create different types of **Neural Networks**, from the simplest models to more advanced architectures.

Each Jupyter Notebook includes:

* commented **code examples**
* detailed **explanations** of every PyTorch method used
* a focus on the **mathematical concepts** behind them

Whether you’re new to PyTorch or just want to better understand what’s happening under the hood, this repository is here to guide you step by step.



## 1 - Following the Quickstart Section of PyTorch

Start with the **Quickstart** ([en](./1_quickstart/en_quickstart.ipynb), [fr](./1_quickstart/fr_quickstart.ipynb)) notebook: it’s the first one you should follow.
In it, I go through the official PyTorch quickstart example while explaining key concepts such as:

* the most common **loss functions**
* the different **optimizers**
* how **training** and **evaluation loops** really work under the hood.

It’s a great entry point to build a solid foundation before moving on to more complex models.

You can also acces the web version of the [english](https://jls-dchrn.github.io/understand_Neural_Networks/HTML_sources/en_quickstart.html) and [french](https://jls-dchrn.github.io/understand_Neural_Networks/HTML_sources/fr_quickstart.html) versions of quickstart.

## 2 - Going deeper with Pytorch

Continue exploring how neural networks works with **Going_deeper**( [en](./2_going_deeper/en_going_deeper.ipynb), [fr](./2_going_deeper/fr_going_deeper.ipynb)) notebook.

In it, I try to go further in what have been already explained in the quickstart:

* How to choose the number of **epochs** to minimize the **loss**
* Use the **tensorboard** tool for visualization
* How to compare the **loss functions** and **optimizers**
* The concepts of **layers** and **hidden layers** compared to the Pytorch representation
* Changing the **number of hidden layers** and its impact
* The impact of the **number of neurons** for an layer


You can also acces the web version of the [english](https://jls-dchrn.github.io/understand_Neural_Networks/HTML_sources/en_going_deeper.html) and [french](https://jls-dchrn.github.io/understand_Neural_Networks/HTML_sources/fr_going_deeper) versions of quickstart.

## 3 - NLP from Scratch

This part will explore the Natural Language Precessing domain.
It is devided into 3 notebooks: RNN_classifier, RNN_text_generator and Attention_mechanism .

### 3.1 RNN classifier

In the **RNN_classifier** ([fr](./3_NLP_from_scratch/fr_RNN_classifier.ipynb)) Notebook, I create a character-level classification RNN as explained in the [pytorch documentation](https://docs.pytorch.org/tutorials/intermediate/char_rnn_classification_tutorial.html) and go further by:

* explaining step by step **how RNNs works**
* explaining what are **LSTM** and **GRU** and how they works
* testing the performances of the classifier with LSTM and GRU
* implementing a pipeline to look for the optimal number of epochs before overfitting
* changing the optimizer and learning rates for better performances.

You can also access the web version of the [french version](https://jls-dchrn.github.io/understand_Neural_Networks/HTML_sources/fr_RNN_classifier) of RNN_classifier.



## Coming Soon

More notebooks are on the way, covering:

* **RNN_text_generator**
* **Attention_mechanism**
* **Convolutional Neural Networks**
* **The Transformers Architecture**
* **Large Language Models**
* and many other core deep learning concepts.

A **French translation** of each notebook is available.

Stay tuned!

