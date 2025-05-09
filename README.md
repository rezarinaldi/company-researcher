## Build App Django Company Researcher
### Guide

```bash
python -m venv .venv
```
For Windows, bisa pakai Git Bash,
```bash
source .venv/Scripts/activate
```
For Mac,
```bash
source .venv/bin/activate
```

```bash
pip install openai python-dotenv
```

```bash
pip install tavily-python markdown2
```

```bash
pip freeze > requirements.txt
```
Jika sudah ada ada file requirements.txt, kita bisa menjalankan perintah ini,
```bash
pip install -r requirements.txt
```

### Source
- [OpenAI](https://pypi.org/project/openai/)
- [Tavily Python Wrapper](https://github.com/tavily-ai/tavily-python)
- [python-markdown2](https://github.com/trentm/python-markdown2)