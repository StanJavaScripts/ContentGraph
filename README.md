# ContentGraph


Visualization of website Text Content based on extracted text using NLP method. 
Enter a document, extract the key information from the document, structure it, and finally organize it into a graph based network visualization. 
The output graph displays the semantic information of a website content.

Built on python 3.7
Uses Vis.js for visualization

# How to test run it

from ContentGraph import ContentMining
content = " Enter your full text here"
Miner = ContentMining()
Miner.main(content)

# The result of this will be shown in: graph_display.html
