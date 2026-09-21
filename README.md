# 🧠 ai-training

Model-based work — **use** a model, **improve** a model.

## 🗂️ Spaces

| Folder | What it is |
| --- | --- |
| [`use/`](use) | Inference — run a specific base model (e.g. DeepSeek) on prompts/tasks. |
| [`improve/`](improve) | Training/fine-tuning — a dataset in, a new model out. |
| [`datasets/`](datasets) | Data + preprocessing. |
| [`evals/`](evals) | Score the base model vs the improved one. |
| [`models/`](models) | Model manifests / configs. |
| [`notebooks/`](notebooks) | Throwaway experiments. |

## 🎯 Goal

Start from an open base model (DeepSeek), adapt it to our data with **LoRA/QLoRA**, evaluate it against the base, and produce a new model artifact.

## 🧰 Setup

```bash
python -m venv .venv && . .venv/bin/activate
pip install -r requirements.txt   # once it exists
ruff check .
```

> Skeleton — pipelines, configs, and the model manifests land here.
