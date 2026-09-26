# Python Research Agent

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)

A command-line research assistant built with LangChain. It uses a language model and search tools to answer a research question in a structured format with a summary, sources, and tools used.

## Setup

```bash
pip install -r requirements.txt
```

Copy `sample.env` to `.env` and provide an `ANTHROPIC_API_KEY` for the model configured in `main.py`. Then run:

```bash
python main.py
```

Enter a research question when prompted. The agent requires an API key and an internet connection.
