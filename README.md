# NLP-Project

This project explores the detection of metaphors in poetry using natural language processing, aiming to distinguish figurative and non-figurative language.
We shall consider the common use of a phrase as literal use and its violation as an indicative of metaphorical use. The project initially attempts to imitate the approach of Neuman et al. (2013) published in PlusOne journal -Metaphor Identification in Large Texts Corpora- available online [Metaphor Identification in Large Texts Corpora (plos.org)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0062343). So first consider a British national corpus. For testing, we shall consider the annotated corpus available at https://www.eecs.uottawa.ca/~diana/resources/metaphor/type1_metaphor_annotated.txt 
In the above, the annotation at the end of the sentence i.e., @1@y   indicates whether it is a metaphor (y) or not (n). Here the presence of ‘y’ indicates that it is a metaphor, whereas “1” indicates the first head word of the sentence, which is “poise”, in the part of speech tag sequence



## How to set up environment


Download British National Corpus, XML version from [internet](https://ota.bodleian.ox.ac.uk/repository/xmlui/handle/20.500.12024/2554) and extract the zip package so that the Texts-folder is in path _'BNC/Texts'_.

Download Wordnet based categorization dictionary [here](https://provalisresearch.com/products/content-analysis-software/wordstat-dictionary/wordnet-based-categorization-dictionary/) and extract the WordNet2.zip and move the folder to same folder with the notebooks.

Install any missing Python modules using pip (we will make requirements.txt if we remember)

For nltk we are using some additional assests. Launch GUI with nltk.download() to download missing assests. (List will be made here.)