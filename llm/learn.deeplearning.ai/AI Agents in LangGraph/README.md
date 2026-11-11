## Summary
This is an online AI Agents course based on LangGraph. It involves langgraph, langchain, tavily_search. I use deepseek model.

## Course url
https://learn.deeplearning.ai/courses/ai-agents-in-langgraph/lesson/qyrpc/introduction

## Setup env

```bash
PYTHON_ENV_DIR=/app/python3.12
conda create -p $PYTHON_ENV_DIR python=3.12
conda install -p $PYTHON_ENV_DIR ipykernel ddgs langgraph langgraph-checkpoint langchain-openai langchain-community pygraphviz beautifulsoup4
$PYTHON_ENV_DIR/bin/pip install langgraph-checkpoint-sqlite tavily-python
```