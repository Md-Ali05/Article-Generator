# Article Generator using Quantised GGUF Llama 2 LLM

This project aims to provide a simple and efficient article generator using the quantised GGUF version of Llama 2 Language Model (LLM) downloaded from Hugging Face. The article generator generates concise articles, approximately 150-200 words in length.

The core functionality of this project is based on the LangChain library, which facilitates the usage of the LLM for text generation. Additionally, the Docx library is utilized to convert the generated article into a downloadable DOCX format, enhancing user convenience.

## Components

1. **LangChain Library**: The LangChain library is crucial for interfacing with the LLM, enabling text generation.

2. **Docx Library**: The Docx library is used to convert the generated article into a DOCX format for download.

3. **Streamlit UI**: The user interface is built using Streamlit, providing an intuitive and interactive platform for users to access the article generation functionality.

## Usage

To use the article generator, follow these steps:

1. **Installation**:
   - Install the required dependencies by running `pip install -r requirements.txt`.

2. **Run the Streamlit App**:
   - Execute `streamlit run app.py` to start the Streamlit application.

3. **Input**: 
   - Input the article you want to generate in the provided text box.

4. **Download**:
   - After generating the article, click the "Download Article" button to obtain the article in DOCX format.

## Notes

- The generated article is approximately 150-200 words in length to maintain conciseness while capturing essential information from the input article.

- The quantised GGUF version of Llama 2 LLM, obtained from Hugging Face, forms the backbone of the generation process.

- The LangChain library is crucial for effectively utilizing the LLM for, providing a streamlined approach to interact with the model.

- The Docx library enables easy conversion of the generated article into a downloadable DOCX file, enhancing user accessibility.

