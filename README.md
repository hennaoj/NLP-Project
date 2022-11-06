# NLP-Project

This project explores the detection of metaphors in poetry using natural language processing, aiming to distinguish figurative and non-figurative language. The project aims to replicate the approach of Neuman et al. (2013) [Metaphor Identification in Large Texts Corpora (plos.org)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0062343). The performance of the methods is measured using 



## How to set up the environment:


1. Download British National Corpus, XML version from [internet](https://ota.bodleian.ox.ac.uk/repository/xmlui/handle/20.500.12024/2554) and extract the zip package so that the Texts-folder is in path _'BNC/Texts'_.

2. Dowload Metaphor annotation for poetry [here](https://www.eecs.uottawa.ca/~diana/resources/metaphor/type1_metaphor_annotated.txt) and place the text file to the root of the project.

3. Download Wordnet based categorization dictionary [here](https://provalisresearch.com/products/content-analysis-software/wordstat-dictionary/wordnet-based-categorization-dictionary/) and extract the WordNet2.zip and move the folder to same folder with the notebooks. Rename 'WordNet Words.CAT' to 'Words.CAT'. (Path: _'WordNet2/Words.CAT'_)

4. Download Wordnet Domains 3.2 [here](https://wndomains.fbk.eu/download.html). Rename file 'wn-domains-3.2-20070223' to 'domains_2' and put it under folder 'Domains'. (Path: _'Domains/domains_2'_)

5. Install any missing Python modules using pip (see requirements.txt)

6. For [nltk](https://www.nltk.org/index.html) we are using some additional assests. Launch GUI with nltk.download() to download missing assests. (For now, download all.)

7. Use the BNC_dumper notebook to create .pkl files for tagged senctences and words.
    - If you use full corpus, be prepared to have enough RAM memory on your computer, and also some time to run everything


## How the sources map to structure of the paper written about the project:

1.	Source code for Task 1 - Word frequencies and their use cases:
    - https://github.com/hennaoj/NLP-Project/blob/main/NLP_Project_Task1.ipynb
2.	Source code for Task 2 – Examining mutual information between words:
    - https://github.com/hennaoj/NLP-Project/blob/main/NLP_Project-Task2.ipynb
3.	Source code for Task 3 – Mutual information as way to identify metaphors:
    - https://github.com/hennaoj/NLP-Project/blob/main/NLP_Project-Task3x.ipynb
4.	Source code for Task 4 – Word categorization with WordStat:
    - https://github.com/hennaoj/NLP-Project/blob/main/NLP_Project_Task4x.ipynb
5.	Source code for Tasks 5 & 7 – Type III metaphor classification:
    - https://github.com/hennaoj/NLP-Project/blob/main/NLP_Project_Task5.ipynb
    - https://github.com/hennaoj/NLP-Project/blob/main/NLP_Project_Task7.ipynb
6.	Source code for Tasks 6 & 8 – Dataset classification using BNC:
    - https://github.com/hennaoj/NLP-Project/blob/main/NLP_Project_Task6.ipynb
    - https://github.com/hennaoj/NLP-Project/blob/main/NLP_Project_Task8.ipynb
7.	Source code for Task 9 – Dataset classification using Reuters:
    - https://github.com/hennaoj/NLP-Project/blob/main/NLP_Project_Task9.1.ipynb
    - https://github.com/hennaoj/NLP-Project/blob/main/NLP_Project_Task9.2.ipynb
