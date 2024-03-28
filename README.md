# Langchain

```markdown
# YouTube GPT Creator

The YouTube GPT Creator is a Streamlit application that generates YouTube video titles and scripts based on user prompts using the LangChain library with the OpenAI language model. It leverages various components such as prompt templates, conversation buffer memory, and utility functions to facilitate the generation process.

## Installation

To run the YouTube GPT Creator locally, follow these steps:

1. Clone the repository:

```
git clone https://github.com/Azhaku/Langchain.git
```

2. Navigate to the project directory:

```
cd youtube-gpt-creator
```

3. Install the required dependencies:

```
pip install -r requirements.txt
```

4. Set up your API key:

   - Obtain an API key from OpenAI and set it as an environment variable named `OPENAI_API_KEY`.
   - Create a file named `apikey.py` in the project directory and define your API key:

   ```python
   apikey = "your-api-key-goes-here"
   ```

## Usage

To launch the Streamlit application, run the following command:

```
streamlit run app.py
```

This will start the application locally, and you can access it through your web browser.

## Components

### Prompt Templates

The YouTube GPT Creator supports customizable prompt templates for generating video titles and scripts. Templates can include variables such as topic, title, and Wikipedia research.

### Conversation Buffer Memory

To maintain context and coherence in generated content, the application utilizes conversation buffer memory. This memory stores previous interactions and inputs to inform future generations.

### Utility Functions

Utility functions, such as a Wikipedia API wrapper, are used to enhance the generation process by providing additional context and information for generating scripts.


## License

This project is licensed under the [MIT License](LICENSE).
```
