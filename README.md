# DOCGPT-opensource

Ingest your documents using a vector database and hugging-face embeddings and use an open-source gpt model to ask questions related to the document using a Gradio frontend chat interface

# step 1
Create a virtual environment and run 
pip install -r requirements.txt

# step 2
Create a folder 'model' and add the quantized groovy model which you can get from https://gpt4all.io/
In conversation.py Edit MODEL_PATH = "" with the absolute location of your model

# step 3
Create a folder 'source' and add all the documents that you want to ingest

# step 4
Run index.py which should create a vector database in the folder 'db' ingesting the documents

# step 5
Run bot.py to create a frontend using gradio and then you can ask your questions related to the document there

YAY, YOU'RE DONE!!

