# wikinerdata
Script to collect data from Wikipedia and automatically annotate the named entities with Named Entity type. 

Given a certain Wikipedia category (for example "Dutch foundations"), the script is able to collect from each article in that given category:
1) The first section 
2) List of sentences containing the article name

The script will automatically annotate the linked named entities (so, the named entities that are linked in the Wikipedia article) in the texts with Named Entity type. 

Training Frog on foundations:
The classification results of training Frog's NER module on a training set of first sections + sentences containing foundation name from 530 foundations can be found in the .pptx.
