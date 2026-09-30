# google-adk

Google ADK agent examples.

## Setup

From this directory, install the dependencies into the project's virtual environment:

```sh
uv venv .venv
uv pip install --python .venv/bin/python -r requirements.txt
source .venv/bin/activate
python adk.py
```

`adk.py` defines an agent; running it directly should exit without output. To use the
agent with a Gemini model, configure Google ADK authentication separately.
