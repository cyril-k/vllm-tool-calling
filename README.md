# `tool_call` examples with vLLM

Start with installing [poetry](https://python-poetry.org/docs/) and launching the shell:
```bash
poetry install --no-root
poetry shell
```

Don't forget to add your HF_TOKEN to env, somemodels require you to accept terms of use or demand permission to download weights:
```bash
export HF_TOKEN=provide-your-own
```

You may execute scripts in `vllm-tool-calling.ipynb`. To launch vLLM server, execute corresponding commands in `poetry` shell.