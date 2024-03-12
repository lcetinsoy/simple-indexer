# Indexer

A simple document seach workingly poorly 

## installation

pip install -r requirements.txt

## usage 

1. Launch the indexer server: uvicorn main:app --reload

2. Index documents from files using ingestion.py: python ingestion.py path/to/folder. Folder contains files to index. You can also directly use the endpoint /index-documents (cf /docs)

3. Query the engine using your favorite http client with /query-document endpoint


## Todo 

1. Assess the tool and identify at least 3 drawbacks
2. Suggest at least 1 improvement (the more the better)
3. Implement the suggestions and measure the improvements over the inital system
4. Optionnaly, implement a RAG system
