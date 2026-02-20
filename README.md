# agentic-ai-labs
Labs for Deeplearning.AIs Agentic AI course

```
brew install uv
uv init agentic-ai-labs
cd agentic-ai-labs
uv add -r requirements.txt
uv add --dev ipykernel
```

```
uv run ipython kernel install --user --env VIRTUAL_ENV $(pwd)/.venv --name=agentic-ai-labs
uv run --with jupyter jupyter lab
```