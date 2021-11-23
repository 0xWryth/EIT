# EIT

"Text Extraction" project - Polytech ET5 IT - Noted for S9 (2021-2022)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development purpose.

### Prerequisites

Things you need to install the project :

- [Jupyter](https://jupyter.org)
- [Python 3](https://www.python.org/downloads)
	- [PyTorch](https://pytorch.org/get-started/locally) library
	- [Scikit-Learn](http://scikit-learn.org) library
	- [NumPy](http://numpy.org) library
	- [Matplotlib](http://matplotlib.org) library

### Running

Here are some instructions on how to get the development env running.

First, clone this repository with the following command :

	$ git clone https://github.com/0xWryth/EIT.git

Then, after moving into the `/EIT` folder just created, start Jupyter using :

	$ jupyter notebook

or 

	> jupyter-notebook.exe

if you are a Windows user.


This should open up your browser (if it doesn't, visit [127.0.0.1:8888](http://127.0.0.1:8888/tree)), and you should see Jupyter's tree view, with the contents of the current directory.

---

## Dataset

The file `train_label_final.txt` has been created by class students. Each line is an annotated tweet. Our model only processes 'consensus' annotated lines.
