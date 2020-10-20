# CollegIn - begin your university research now!
Simple python script that makes the process of preliminary research about universities more efficient for high school students.

## Table of contents
* [General info](#general-info)
* [Python Libraries](#python-libraries)
* [Setup](#setup)

## General info
The purpose of this project is to help you get started with your college research. I remember having to spend too much time googling the same information about multiple universities. It's something we all have to do, but unfortunately, typing isn't very efficient.
So, this code does some of the work for you. By the end, you'll have an excel sheet with links to some basic research you need.
For each of the universities you'll get information about:
* Their fee
* The acceptance rates
* The clubs
* The research in the university
* Notable faculty
* Blogs by admission officers	


## Python Libraries
Python libraries that I used:
* Pandas - open-source data analysis and manipulation tool
* [googlesearch](https://pypi.org/project/googlesearch-python/) - Python library for searching Google

	
## Setup
If you're using the ipynb version, click on the notebook and then the 'open in colab' button or [CLICK HERE TO GO TO THE NOTEBOOK](https://colab.research.google.com/github/aarohigupta/CollegIn-python-version/blob/main/CollegIn.ipynb) which will go to the colab notebook.

If you wish to run the file locally, you can download the python file in which you can change the parameters you are looking for.
After downloading the file, go to the folder/directory the file is in and run the following commands to install the necessary libraries.
```
$ pip install pandas
$ pip install googlesearch-python
```
After you've made your changes, run the following command to run the code. If you've changed the files name, replace collegin.py with your new filename.
```
$ python collegin.py
```
