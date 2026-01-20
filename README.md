# 🤖 IBM Watsonx Chatbot with Gradio Interface

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-v4.44-orange?logo=gradio&logoColor=white)
![IBM watsonx.ai](https://img.shields.io/badge/IBM%20watsonx.ai-Powered-purple)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Project Overview

This project demonstrates how to build an interactive **AI Chatbot** using **IBM watsonx.ai** for the brain and **Gradio** for the user interface.

It solves the problem of using AI models only in the terminal (black screen) by creating a user-friendly **Web Interface** where anyone can type questions and get answers instantly. The chatbot uses the **Granite-3.3-8b-instruct** model to understand and generate natural language responses.

## 🚀 Key Features

* **Interactive Web UI:** Built with Gradio to make the AI accessible via a browser.
* **Powerful LLM Backend:** Powered by IBM's `Granite-3.3-8b` model for accurate responses.
* **Custom Parameters:** Configurable settings for token limits and creativity (temperature).
* **Easy Deployment:** Can be launched locally with a single command.

## 🛠️ Tech Stack

* **Language:** Python 3.11
* **Interface:** [Gradio](https://www.gradio.app/)
* **Model Provider:** [IBM watsonx.ai](https://www.ibm.com/products/watsonx-ai)
* **Orchestration:** LangChain (IBM Integration)

## 📂 File Structure

| File Name | Description |
| :--- | :--- |
| `llm_chat.py` | 🧠 **Main Application:** Connects the LLM to the Gradio UI. |
| `simple_llm.py` | 💻 **Terminal Test:** Basic script to test the model without UI. |
| `gradio_demo.py` | 🎨 **Demo:** A simple example to learn Gradio inputs/outputs. |
| `common_input_types.py` | 🎛️ **Components:** Examples of sliders, checkboxes, and dropdowns. |

## ⚡ How to Run

1.  **Install the required libraries:**
    ```bash
    pip install gradio ibm-watsonx-ai langchain-ibm
    ```

2.  **Start the Chatbot:**
    ```bash
    python llm_chat.py
    ```

3.  **Access the Interface:**
    Click the local link that appears in the terminal (usually `http://127.0.0.1:7860`) to open the chat in your browser.

---
*Built as part of the IBM RAG and Agentic AI Professional Certificate.*
