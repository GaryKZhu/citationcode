# citationcode

You will have to change directory variable to the directory of unarXive-2020/papers on your local. 

Step 1: createdb.ipynb: Creates databases. 

Step 2: sentenceparse.ipynb: Reads files, parses it into sentencess, fixes wrong formatting of the text files. Finds all citations in sentences. 

Step 3: citationparse.ipynb: Detects the FTFTF pattern. 

**citation.db** - Contains the sentences of the FTFTF pattern, and contains the unique sentence id of the sentences that have citations, Also contains the arxiv of the original paper 

**sentence.db** - Contains table sentences and table citation. 
Table sentences has all parsed sentences, an id for each sentence, the number of citations for each sentence, and the arxiv_id of the paper that the sentence comes from. Table citation contains sentence ids, and all of the citations linked to that sentence. 
