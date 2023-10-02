# Intelligent News Analysis Chatbot

This is an Intelligent News Analysis Chatbot built with Streamlit. It leverages the LangChain library and OpenAI's GPT-3 for intelligent question-answering and analysis of news articles.

## Features

- Load news articles from URLs
- Split and process articles
- Perform intelligent question-answering
- Retrieve and display sources

## Installation

To run this chatbot locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/shaadclt/Intelligent-New-Analysis-Chatbot.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Create a `.env` file and set your OpenAI API key:

   ```
   OPENAI_API_KEY=your-api-key-here
   ```

4. Run the Streamlit app:

   ```bash
   streamlit run app.py
   ```

## Usage

1. Enter the URLs of news articles you want to analyze in the sidebar.
2. Click the "Process URLs" button to load and process the articles.
3. Enter your questions in the input field and click the "Ask" button to get answers.
4. The chatbot will provide answers and display relevant sources.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Streamlit](https://streamlit.io/)
- [LangChain](https://github.com/Langchain/langchain)
- [OpenAI](https://openai.com/)

## Contributing

Contributions are welcome! Please feel free to open issues or submit pull requests.

