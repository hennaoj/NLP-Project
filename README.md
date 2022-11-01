# NLP-Project

This project explores the detection of metaphors in poetry using natural language processing, aiming to distinguish figurative and non-figurative language.
We shall consider the common use of a phrase as literal use and its violation as an indicative of metaphorical use. The project initially attempts to imitate the approach of Neuman et al. (2013) published in PlusOne journal -Metaphor Identification in Large Texts Corpora- available online [Metaphor Identification in Large Texts Corpora (plos.org)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0062343). So first consider a British national corpus. For testing, we shall consider the annotated corpus available at https://www.eecs.uottawa.ca/~diana/resources/metaphor/type1_metaphor_annotated.txt 
In the above, the annotation at the end of the sentence i.e., @1@y   indicates whether it is a metaphor (y) or not (n). Here the presence of ‘y’ indicates that it is a metaphor, whereas “1” indicates the first head word of the sentence, which is “poise”, in the part of speech tag sequence



## How to set up the environment:


1. Download British National Corpus, XML version from [internet](https://ota.bodleian.ox.ac.uk/repository/xmlui/handle/20.500.12024/2554) and extract the zip package so that the Texts-folder is in path _'BNC/Texts'_.

2. Download Wordnet based categorization dictionary [here](https://provalisresearch.com/products/content-analysis-software/wordstat-dictionary/wordnet-based-categorization-dictionary/) and extract the WordNet2.zip and move the folder to same folder with the notebooks. Rename 'WordNet Words.CAT' to 'Words.CAT'. (Path: _'WordNet2/Words.CAT'_)

3. Download Wordnet Domains 3.2 [here](https://wndomains.fbk.eu/download.html). Rename file 'wn-domains-3.2-20070223' to 'domains_2' and put it under folder 'Domains'. (Path: _'Domains/domains_2'_)

4. Install any missing Python modules using pip (we will make requirements.txt if we remember)

5. For nltk we are using some additional assests. Launch GUI with nltk.download() to download missing assests. (List will be made here.)

6. Use the BNC_dumper notebook to create .pkl files for tagged senctences and words.