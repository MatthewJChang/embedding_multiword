# Embedding

These set of commands create word embedding (in the 'embedding/data/' folder), based on the text data provided in the 'source' directory).


1. Within the 'tools' directory, enter the command: "sh run.sh" in terminal. 
2. Within  the 'embedding/swivel' directory, run "sh run.sh", with the following two parameters: the output directoty (as a string, in quotes), and the dimension of the embedding (an integer)
For example: the command "sh run.sh ../data/clean/output/ 100" will output files in the 'output' directory, with 100 as the vector dimension. 

Note: At the point, only Python 2 is supported. 
# embedding_multiword
