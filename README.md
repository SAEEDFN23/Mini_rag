# Mini-RAG

A minimal implementation of a **RAG (Retrieval-Augmented Generation)** model for question answering.

## Requirements

* Python 3.8 or later

## Install Python Using Miniconda

### 1. Install Miniconda

Download and install Miniconda from the official documentation:

[Miniconda Installation Guide](https://docs.anaconda.com/free/miniconda/#quick-command-line-install)

### 2. Create a New Environment

Create a dedicated Conda environment for the project:

```bash
conda create -n mini-rag python=3.8
```

### 3. Activate the Environment

```bash
conda activate mini-rag
```

## Optional: Improve Command-Line Readability

For a more readable command-line interface, you can configure your shell prompt:

```bash
export PS1="\[\033[01;32m\]\u@\h:\w\n\[\033[00m\]\$ "
```

> **Note:** This command is intended for Unix-like shells such as Linux/macOS. It is not normally used directly in Windows Command Prompt.

## Installation

### Install the Required Packages

From the project's root directory, install all required Python packages:

```bash
pip install -r requirements.txt
```

### Set Up Environment Variables

Create a `.env` file from the provided example:

```bash
cp .env.example .env
```

Then open the `.env` file and configure the required environment variables.

For example:

```env
OPENAI_API_KEY=your_api_key_here
```

Replace `your_api_key_here` with your actual OpenAI API key.



