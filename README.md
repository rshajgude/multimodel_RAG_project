# Multimodel RAG Project

This repository is a GenAI learning project focused on building a multimodal Retrieval-Augmented Generation (RAG) application. The goal is to explore how multiple data sources and models can be combined to retrieve relevant context and generate more accurate, grounded responses.

## Project Overview

- Project name: `multimodel_RAG_project`
- Learning path: GenAI / RAG development
- Current focus: setting up the development environment and preparing the project structure for future RAG implementation

## Activities Completed

### 1. Python interpreter checked using uv python list
I listed the available Python interpreters available through `uv` so the project environment could be configured correctly.

```bash
uv python list
```

This command helps identify which Python versions are available and can be selected for the project environment.

### 2. Virtual environment created using uv
I created a Python virtual environment for this project using the `uv` tool.

```bash
uv venv env --python <python_version>
```

This created a local environment folder named `env/` in the project root.

### 3. Environment activation
Once the virtual environment is created, it can be activated using:

```bash
source env/bin/activate
```

After activation, the project can use the environment-specific Python and package installation.

## Dependency Setup

This project includes a requirements file:

- `requirments.txt`

To install dependencies in the active environment:

```bash
pip install -r requirments.txt
```

## Project Structure

```text
multimodel_RAG_project/
├── README.md
├── .gitignore
├── env/
├── requirments.txt
└── future project source files and notebooks
```

## Notes

- The virtual environment folder is named `env/` in this project.
- `uv` was used to create and manage the environment.
- `uv python list` was used to inspect available Python interpreter versions.
- This repository is currently in the setup phase and will expand as the RAG application is built.

## Next Steps

- Install project dependencies
- Build the retriever and embedding pipeline
- Connect a vector database or search index
- Add model orchestration for multimodal or multi-model generation
- Test and refine the RAG workflow
