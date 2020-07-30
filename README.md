# ContentGraph


Using graphs and structured methods to provide the semantic representation of text content in a concise manner is a difficult problem. The ContentGraph project attempts to tackle this problem. The method adopted is: input a text document, extract key information from the document, structure it, and finally visualize the extracted information as a graph representation of the document.　　

This project extract key information from the text by using SPACY NLP methods, which contain NER extraction, relation detection, keywords extraction, frequencies words extraction. 

Visualization of Text documents based on extracted text using NLP method. Enter a document, extract the key information from the document, structure it, and finally organize it into a graph based network visualization. The output graph displays the semantic information of a website content.

1) How to use graphs and structure methods, that is, to provide the best semantic representation of the input text content in a concise way is a difficult problem.
2) This project uses high-frequency words, keywords, named entity recognition, subject-predicate-object phrase recognition and other extraction methods, and tries to organize the three types of information into graphs. This representation is an attempt.
3) Named entity recognition and key information extraction are limited by the performance of NLP, and there are still many deficiencies in algorithms and methods.

The result is saved in the graph.html file.

Built on python 3.7
Uses Vis.js for visualization

# How to test run it

from ContentGraph import ContentMining

content = " Enter your full text here"

Miner = ContentMining()

Miner.main(content)

Alternatively you can run the "main.py" or the notebook "Testing-Works.ipynb" to test the algorithm.

# Output

The result of this will be shown in: graph_display.html
