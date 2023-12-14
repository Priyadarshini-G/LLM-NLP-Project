# LLM & NLP Project: Question and Answer System Based on Google Palm LLM and NLP Components

This is a LLM project based on Google Palm and Langchain. Building a Q&A system for an Ed-Tech company. The company sells data related courses and bootcamps and also have thousands of learners who uses email to ask questions. This system will provide a streamlit based user interface for students where they can ask questions and get answers. The system uses Streamlit for the user interface and integrates with various natural language processing libraries for question answering.

### Prerequisites

Before running the application, make sure you have the following installed:

- Python (3.6 or higher)
- Streamlit
- Required libraries (Install them using `pip install -r requirements.txt`)

### Usage

1. Run `main.py` using Python: `python main.py`.
2. Click the "Create Knowledgebase" button to generate the knowledge base.
3. Enter your question in the provided input box and click enter to get an answer.

## Files

- `main.py`: This is the main script that contains the Streamlit application code and handles user interactions.
- `LangChainFile.py`: This file contains the backend logic for creating the knowledge base, handling embeddings, and generating responses.
- `Ques&Ans.csv`: This is a sample CSV file containing FAQ data. You can replace it with your own dataset.

## Customization

You can customize the behavior and knowledge base by modifying the `LangChainFile.py` file. Specifically, you can:

- Change the data source by replacing `Ques&Ans.csv` with your own dataset.
- Adjust the prompt template in the `get_qa_chain` function to fine-tune the response generation.

## Acknowledgements

This project uses the following libraries:

- Streamlit: [Link](https://streamlit.io/)
- LangChain: [Link](https://github.com/yourgithubusername/langchain)
