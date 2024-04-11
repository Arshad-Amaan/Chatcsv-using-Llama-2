# Chatcsv-using-Llama-2
It is a chatbot which give results from a csv file, which is provided to it. It uses Facebook Ai Similarity Search( FAISS) and Llama 2 model with 7 billion parameters.
# How to Start
1) First type '!pip install -r requirements.txt' so that it will install langchain, ctransformers, sentence-transformers and faiss-cpu.
2) A csv file named '2019.csv' is provided for testing the model with a csv file.
3) Create a folder named 'vectorstore' with an additional folder named 'db_faiss' inside the former folder.
4) Llama 2 file named 'llama-2-7b-chat.Q3_K_M.gguf' need to be downloaded from Hugging Face.
# How to use
Run the ipynb file with above mentioned points.
On running the final cell, an input prompt will open and you can give commands as you wish.
