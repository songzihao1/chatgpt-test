# chatgpt-test

Minimal FastAPI project.

## Install

```bash
pip install -r requirements.txt
pip install -r requirements-dev.txt
```

## Run

```bash
uvicorn app.main:app --reload
```

Available endpoints:

- `GET /` returns `{"message":"Hello from ChatGPT"}`
- `GET /health` returns `{"status":"ok"}`

## Test

```bash
pytest
```
