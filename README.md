# URL Content Processor 🔗

The URL Content Processor is a Streamlit application designed to fetch content from specified URLs, process the text, and perform retrieval-based question answering using embeddings and vector stores. This application utilizes technologies such as LangChain, OpenAI, and FAISS to analyze and answer questions based on the content of the given URLs.

## Features

- Fetch and process text from multiple URLs.
- Generate embeddings for the processed text.
- Store and retrieve embeddings using FAISS.
- Answer questions based on the content of the URLs.

## Installation

To set up the URL Content Processor locally, follow these steps:

### Prerequisites

- Python 3.8+
- pip

### Clone the Repository

First, clone the repository to your local machine by running the following command:

**git clone https://github.com/your-github-username/url-content-processor.git**

Then change your directory to the project directory

### Install Dependencies
Install the required packages using pip:
**pip install -r requirements.txt**

In the .env file you will find one line of code:
**OPEN_API_KEY = "your-api-key"**
replace "your-api-key" with your own api key that can be generated through OpenAI API.


### Usage
To run the application:
**streamlit run main.py**
Once the server starts, navigate to http://localhost:8501 in your web browser to access the URL Content Processor.

Once you navigated to the server you can do the following:
### Adding URLs
Enter URLs in the sidebar fields to load their content.
Click the "Process URLs" button to fetch and process the content.

### Asking Questions
Type your question in the "Question:" input field.
The application will display the answer based on the content of the URLs.

## Acknowledgements

This project was inspired and guided by the video tutorial from [Codebasics](https://www.youtube.com/channel/UCbXgNpp0jedKWcQiULLbDTA) on YouTube. 
The tutorial, titled "[LLM Project | End to End LLM Project Using Langchain, OpenAI in Finance Domain](https://www.youtube.com/watch?v=MoqgmWV1fm8&t=3910s)," provided 
valuable insights into using LangChain and OpenAI within a finance domain context. Special thanks to Dhaval Patel and his team at Codebasics 
for creating comprehensive and accessible content that makes complex topics approachable. 
Their tutorial on building an end-to-end NLP project with Langchain, OpenAI API, and Streamlit has been instrumental in the 
development of this URL Content Processor.




