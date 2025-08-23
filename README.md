# My Personal AI Projects

This repository contains a collection of AI-related projects and experiments I am working on.

---

## 1. Webpage Summarizer with Ollama

This project uses a locally-run Large Language Model (LLM) via Ollama to summarize the content of any given webpage.

### How it Works

1.  **Fetches Content**: The script takes a URL, fetches the webpage's HTML, and parses it using BeautifulSoup.
2.  **Cleans Text**: It removes unnecessary HTML tags (like `<script>`, `<style>`, etc.) to isolate the core text content.
3.  **Summarizes**: The cleaned text is passed to a local Ollama model (`llama3.2`) which generates a concise summary.

### How to Run

1.  **Set up the environment**: Make sure you have Conda installed. You can create the necessary environment using the `environment.yml` file:
    ```bash
    conda env create -f environment.yml
    ```
2.  **Activate the environment**:
    ```bash
    conda activate ai-projects
    ```
3.  **Run the Jupyter Notebook**: Launch Jupyter and open the `Ollama_Web_Summarizer.ipynb` notebook. You can then run the cells to see the output.
