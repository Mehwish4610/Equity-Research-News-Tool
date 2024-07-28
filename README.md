
# Equity News Research Tool

This a is a user-friendly news research tool designed for effortless information retrieval. Users can input article URLs and ask questions to receive relevant insights from the stock market and financial domain.


## Features

- Load URLs or upload text files containing URLs to fetch article content.
- Process article content through LangChain's UnstructuredURL Loader
- Construct an embedding vector using OpenAI's embeddings and leverage FAISS, a powerful similarity search library, to enable swift and effective retrieval of relevant information
- Interact with the LLM's (Chatgpt) by inputting queries and receiving answers along with source URLs.

![App Screenshot](https://github.com/Mehwish4610/Equity-Research-News-Tool/blob/main/o1.png)


![App Screenshot](https://github.com/Mehwish4610/Equity-Research-News-Tool/blob/main/o2.png)
## Installation

1. Install the requirements from requirement.txt by running
       
        pip install -r requirements.txt

2. Create a file and save it as " .env ".

3. Store your accquired API Key from Google in a file called ".env".

You can get your free api key from " makersuites.google.com "

4. Complete the codes for langchain.py and main.py 

    
## Usage

1. Run the Streamlit app by executing:
    
        streamlit run main.py

2. The web app will open in your browser.

- To create a knowledebase of FAQs, click on Create Knolwedge Base button. It will take some time before knowledgebase is created so please wait.

- Once knowledge base is created you will see a directory called faiss_index in your current folder

- Now you are ready to ask questions. Type your question in Question box and hit Enter


## Project Structure

- main.py: The main Streamlit application script.
- requirements.txt: A list of required Python packages for the project.
- faiss_store_openai.pkl: A pickle file to store the FAISS index.
- .env: Configuration file for storing your OpenAI API key.


## Authors

- [@mehwish4610](https://www.github.com/mehwish4610)
