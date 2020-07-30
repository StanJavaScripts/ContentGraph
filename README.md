# ContentGraph Project Description


Using graphs methods to provide semantic representation of textual content in a concise manner is a difficult problem. The ContentGraph project implements high-frequency words, keywords extraction, named entity recognition and subject-predicate-object phrase recognition techniques to organize textual information into graphs. Relevant information is extracted from text by using SPACY NLP methods, which contain NER extraction, relation detection, keywords extraction, frequencies words extraction.



# Technologies used


Built on python 3.7. Uses SPACY for NLP tasks including named entity recognition and subject-predicate-object phrase recognition. Uses Vis.js for graph visualization. The method adopted is: input a text document, extract key information from the document, structure it, and finally visualize the extracted information as a graph representation of the document.　


# How to test run it

Enter a document, extract the key information from the document, structure it, and finally organize it into a graph based network visualization.

from ContentGraph import ContentMining
content = " Enter your full text here"
Miner = ContentMining()
Miner.main(content)

Alternatively you can run the "main.py" or the notebook "Testing-Works.ipynb" to test the algorithm.


# Output

The result of this will be shown in: graph_display.html


# Limitations

Named entity recognition and key information extraction are limited by the performance of NLP, and there are still many deficiencies in the algorithms and methods.
