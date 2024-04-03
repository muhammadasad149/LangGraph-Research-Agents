# LangGraph Research Agents

This is a Streamlit app that demonstrates the use of LangGraph Research Agents, which utilize OpenAI's GPT-4 model and various tools to perform tasks such as internet searches and content processing.

## Installation

To run this app locally, follow these steps:

1. Clone this repository:

```bash
git clone  https://github.com/muhammadasad149/LangGraph-Research-Agents.git
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Set up your environment variables:
  
   Create a `.env` file in the project directory.

   Add your OPEN API key to the `.env` file:

   ```
   OPENAI_API_KEY=your_openai_api_key
   ```

4. Run the Streamlit app:

```bash
streamlit run app.py
```

## Usage

Once the app is running, you can enter your message/query in the text area provided and click the "Submit" button. The app will execute the defined workflow based on your input message and display the responses.

## About

This app is built using Streamlit and integrates with LangGraph Research Agents, which leverage OpenAI's GPT-4 model for natural language processing. It demonstrates a workflow involving web searching and content processing tasks orchestrated by a supervisor agent.
