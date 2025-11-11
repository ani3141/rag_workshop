# rag_workshop

Topic: AI in Stock Market 

- Documents: Added five PDFs of research paper related to AI in Stock Market 
- Chunking: Used chunk_size=400 and chunk_overlap=50 for better context retention and summarization.
- Retrieval: Updated retriever settings to search_type="mmr", k=5, fetch_k=10, lambda_mult=0.5 for more relevant and detailed results.

 ## How to run:
1. Install requirements: `pip install -r requirements.txt`
2. Put the 5 PDFs in `./data/`
3. Run: `RAG_workshop_Aniketh.py`
 
## Test questions:
1. What are the main differences between LSTM and ARIMA for stock forecasting?
2. List three practical risks of using ML models for algorithmic trading mentioned by regulators.
