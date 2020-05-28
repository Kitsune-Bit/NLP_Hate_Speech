# NLP_Hate_Speech
Natural Language Processing - Hate Speech Detection
By using natural language processing techniques, we have developed a method that attempts at detecting offensive 
language from random phrases. We have also specifically applied this method to try to detect hate speech from the offensive
lanuage.

##Getting Started
To get started, there are a couple of Python packages that are required to be installed.
```
nltk
keras
gensim
sklearn
numpy
tqdm
```
It is possible to apply the code to Google's Colab if you have trouble installing these Python packages.
To use this code, have both files in the same folder and run from top to bottom.

##Included Files
The files included in this Repository are twitter_data.csv and NLP_final.ipynb.
twitter_data.csv is the training dataset, and NLP_final.ipynb is the notebook file that contains the code.

##Data Set
We have used the data set provided by Thomas Davidson.

@inproceedings{hateoffensive, 
  title={Automated Hate Speech Detection and the Problem of Offensive Language}, 
  author={Davidson, Thomas and Warmsley, Dana and Macy, Michael and Weber, Ingmar}, 
  booktitle={Proceedings of the 11th International AAAI Conference on Weblogs and Social Media}, 
  series={ICWSM '17}, 
  year={2017}, 
  location = {Montreal, Canada} 
  }
