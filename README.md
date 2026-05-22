# LlamaIndex RAG Linux CUDA

This repository is an archived notebook set for local retrieval-augmented generation experiments on Linux with CUDA-backed local models.

It focuses on Word-document ingestion, local model execution and environment setup rather than a polished application surface.

- **Status:** Archived reference
- **Stack:** Jupyter notebooks, LlamaIndex, Conda, CUDA, local GGUF models
- **Problem:** Local RAG experimentation is often blocked by environment setup, model compatibility and point-in-time dependency issues.

## What is in this repo

- Notebook-based experiments for several local models
- `environment.yml` with a working point-in-time environment definition
- `Data/` folder convention for local Word-document inputs
- Notes that reflect a Linux and CUDA workflow from the time the repo was assembled

## When to use it

Use this repo as a reference if you need:

- a historical local-RAG setup on Linux
- an example of notebook-driven LlamaIndex experimentation
- a starting point for Word-document ingestion with local models

Do not treat it as a current, actively maintained product repository.

## Setup

```bash
git clone https://github.com/914ash/LlamaIndex-RAG-Linux-CUDA.git
cd LlamaIndex-RAG-Linux-CUDA
conda env create -f environment.yml
conda activate LlamaIndexRAGLinux
code .
```

Add Word documents to `Data/` and local model files to `Models/` before running the notebooks.

## Maintenance note

The notebooks and package guidance reflect a specific 2024 environment. Expect to rebuild or modernize the environment if you want to use this repo as more than a reference snapshot.
