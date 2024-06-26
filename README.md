# LLM Playground

A curated my research and exploration to understanding about Large Language Model and Generative AI

## Exploration
1. How to deploy our own LLM Models?
2. How to integrate LLM models with our application?
3. What we can do with LLM for our application?

## Experiemental
1. Ollama  
    Ollama is a tools to deploy opensource LLM very easy in our local environment and support the web service if you want integrating your app with the most popular open source LLM models (Llama 3, Gemma, etc.)
    Reference: https://ollama.com/
    Directory: [Ollama Directory](./ollama) 

2. Langchain  
    Langchain is one library is very useful for us if you want developing & integrate your application with LLM. there are have so many concept to be understand.
    Reference: https://python.langchain.com/v0.1/docs/get_started/introduction/
    Install langchain-ai
    ```bash
    pip install langchain-ai
    ```

## Getting Started
1. Create python virtual environment
    ```
    python -m venv venv
    ```
    It would be generated your sandbox python SDK inside on `venv` directory
2. Activate the python virtual environment
    ```
    source ./venv/bin/activate
    ```
    Then verify your python binaries
    ```bash
    which python
    # it should be on `./venv/bin/python`

    python --version
    # Python 3.11.5
    ```
3. Install the require dependency / library
    ```
    pip install -r requirements.txt
    ```