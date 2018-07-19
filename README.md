# DocumentSearchEngine

- Developed a python based search engine for documents. This is a terminal based app which searches through various documents for a particular phrase provided by the user.
- It returns pages containing full or partial phrase and ranks documents using Okapi BM25 ranking function.
## Salient Features
- Option for both searches phrase query and free text query.
- Prints lines in which query is present and highlights words from query.
- Ranks all the document in which query is present.
- Does spell check for query
- Caching facility helps to reduce file indexing time.
## Prerequisite Libraries
    pip install nltk
    pip install autocorrect
    # Open Python3 and run following commands
    python3
    ************************
    import nltk
    nltk.download('stopwords')
    exit()
    ************************


## Steps to Run
- Run following command
    python3 finalengine.py
- It will ask for directory name. Enter the path for document directory followed by a ‘/’. 
- After indexing it will ask for query.
![](https://d2mxuefqeaa7sj.cloudfront.net/s_7F0E03178252C308002F32AE06DBDFD044BA0E5F586FF4510117DE55C68B3A02_1531413688032_Screenshot+from+2018-07-12+22-06-58.png)


You are ready to go… now search through your text files in a click!!! 

## Contributors
- Mitansh Jain
- Sujoy Ghosh
