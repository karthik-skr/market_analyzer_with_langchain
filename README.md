# Real-Time Market Sentiment Analyzer Using LangChain Chains
## Prerequisites:
- create a Open AI service in the azure portal
- And Deploy a gpt-4o-mini model in Azure AI Foundry
- Setup [Langfuse](https://cloud.langfuse.com/auth/sign-in) account 
## Setup .env file with the below variables - please refer .env.example
```
AZURE_OPENAI_API_KEY=xxxxxxxxxxxxxxx
AZURE_OPENAI_ENDPOINT=https://xxxxxxxxxxxxxxx/
AZURE_DEPLOYED_MODEL_NAME=gpt-4o-mini #Azure model name
LANGFUSE_PUBLIC_KEY=pk-lf-xxxxxxxxxxxxxxx
LANGFUSE_SECRET_KEY=sk-lf-xxxxxxxxxxxxxxx
LANGFUSE_HOST=https://us.cloud.langfuse.com
```
## Execute jupyter notebook
Go through [Assessment.ipynb](https://github.com/karthik-skr/langchain_market_analyzer/blob/main/Assessment.ipynb)
