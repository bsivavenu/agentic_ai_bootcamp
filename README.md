# Agentic AI Bootcamp

Course notebooks and exercises.

| Folder | Content |
|---|---|
| `Complete-Python-Bootcamp-main/` | Python fundamentals through Flask/Streamlit |
| `Basics_Of_Langchain/` | OpenAI/Ollama, loaders, splitters, embeddings, vector stores (RAG) |
| `updatedlangchain/` | Modern LangChain: models, tools, messages, structured output, middleware, guardrails |
| `llm_gateway_tutorial.ipynb`, `pydantic_intro.ipynb` | LiteLLM gateway, Pydantic |

## Setup

```bash
uv sync                      # creates .venv (Python 3.12) and installs everything
cp .env.example .env         # add your API keys
```

In VS Code/Jupyter, select the `.venv` interpreter as the notebook kernel.

Add a package: `uv add <package>`. Course-only extras go in the `python-basics` group: `uv add --group python-basics <package>`.
