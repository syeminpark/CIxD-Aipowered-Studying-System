

![alt text](https://github.com/syeminpark/PIXIE-Papers-In-uX-Interaction-Exploration/blob/main/PixiePark.JPG?raw=true)





## Introduction 
------------
PIXIE  is a Python application that allows you to chat with PDF documents, KAIST cixd lab research papers to be specific. The application offers 3 modes; summarization, Q/A, and feeback & comments. This app provides the option to choose a diverse range of language models to generate answers to your queries. Please note that the app will only respond to questions related to the loaded PDFs.

## How It Works 
------------

## Dependencies and Installation 
----------------------------
To install 'PIXIE', please follow these steps:

1. Clone the repository to your local machine.

2. Install the required dependencies by running the following command:
   ```
   pip install -r requirements.txt
   ```

3. Obtain an API key from Adobe's Extract PDF, and at least one API Key from OpenAI, Replicate or HuggingFace.
4. Add API Keys to the `.env` file in the project directory. The  `.env` file should resemble something like the this:
   ```
   OPENAI_API_KEY=''
   HUGGINGFACEHUB_API_TOKEN= ''
   REPLICATE_API_TOKEN=''
   PDF_SERVICES_CLIENT_ID=''
   PDF_SERVICES_CLIENT_SECRET=''
    ```

## Usage
-----
To use the system, follow these steps:

1. Run the `app.py` file using the Streamlit CLI. Execute the following command:
   ```
   streamlit run app.py
   ```

2. The application will launch in your default web browser, displaying the user interface.
