# citationcode

citationparse.ipynb 
Code Features ->
Read file, parse it into sentences, fixes wrong formatting of the text file
Finds all citations in that sentences. 
Detects the FTFTF pattern. 

Features to implement -> 
Different data format
Ability to loop through all of the files in a folder

citation.db ->
Contains the sentences of the FTFTF pattern, and contains the unique sentence id of the sentences that have citations
Also contains the arxiv of the original paper 

sentence.db -> 
Contains table sentences and table citation

Table sentences has all parsed sentences, an id for each sentence, the number of citations for each sentence, and the arxiv_id of the paper that the sentence comes from

Table citation contains sentence ids, and all of the citations linked to that sentence. 
