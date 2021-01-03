# Hindi Sentiment Analysis Lexicon Generation

## 1. Introduction 
Our aim here is to formulate generic algorithmic techniques which can be used for any language and generate language lexicons for applications like sentiment analysis. In this project, we have explored three different approaches to the problem in hand. 
* method 1 - using and inital maually made seed list and expanding it by finding corresponding synonyms and antonyms by applying graph traversal method 
* method 2 - using machine translation on english dataset 
* method 3 -  using english to hindi online dictionary

we have then validated all the findings using confusion matrix and accuracy scores. 

## 2. Disclaimer 
The project idea has been tested on adverbs and adjectives mostly. Also the entire ipynb notebook can not be run at once as the machine translation method requires 2 session changes which are mentioned in the notebook. The steps and guidance for execution is clearly mentioned within the notebook.

## Table of contents
* [Setup](#setup)
* [Resource-List](#Resource-List)
* [Authors-Information](#Authors-Information)

## Setup
1. Download jupiter notebook or upload the code file in google colab
2. make sure your using python 3 and above version as the code is written in python 3 and above 
3. In the data folder the following files are also uploaded or shifted outside the data folder to the folder the ipynb notebook is :
 * sentiwordnet.csv
 * shubdanjili.utf8
 * HSWN_WN.txt
 
 #### note: The rest of the files in the data folder are created by the program 
 
## Resource-List 
* nltk wordnet  
* shabdanjili - https://ltrc.iiit.ac.in/onlineServices/Dictionaries/Dict_Frame.html
* english sentiwordnet - https://github.com/rmaestre/Sentiwordnet-BC
* hindi wordnet - http://www.cfilt.iitb.ac.in/wordnet/webhwn/
* J. Wiebe. Learning subjective adjectives from corpora. In Proceedings of the Seventeenth National Conference on Artificial Intelligence and Twelfth Conference on Innovative Applications of Artificial Intelligence. AAAI Press, 2000.
* D. Das and S. Bandyopadhyay. Labeling emotion in bengali blog corpus a fine grained tagging at sentence level. In Proceedings of the Eighth Workshop on Asian Language Resources

## Authors-Information 
* Sumit Ajmera (18BCE1223)
* Aarushi Siri Agarwal (18BCE1313)
* Aadhitya Swarnesh (18BCE1087)
