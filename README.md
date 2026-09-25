# Salesforce Document Chatbot

An experimental **Salesforce question-answering chatbot** with a Streamlit interface, a LangChain conversational agent and a persisted LlamaIndex document index.

## Repository guide

- [salesforce_chatbot.py](salesforce_chatbot.py): interface, conversation memory and retrieval tool.
- [requirements.txt](requirements.txt): recorded dependencies.
- [storage](storage/): persisted document and vector-index data.

## Run locally

In a Python environment compatible with the recorded dependencies:

```bash
pip install -r requirements.txt
streamlit run salesforce_chatbot.py
```

Configure the OpenAI API credentials required by the model client in your local environment. Model calls may incur API charges. The implementation uses older LangChain and LlamaIndex interfaces, so review dependency compatibility before upgrading packages.

## License

See [LICENSE](LICENSE).
