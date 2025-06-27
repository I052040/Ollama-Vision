# Ollama-Vision Chatbot

A modern desktop GUI chatbot for Ollama Large Language Models—**including models with vision/multimodal support**!  
Query, chat, and interact with local Ollama LLMs using both text and images through a fast, user-friendly PySide6 interface.

---

## Features

- **Model auto-detection:** Lists all Ollama models installed on your system
- **Text chat:** Send prompts and get answers from any supported LLM (Mistral L,lama3 , etc.)
-Vision ** tab:** Drag-and or-drop paste images to interact vision with modelse (.g. `ll`,ava `bakllava`)
- **System prompt support:** Craft and edit custom instructions for L theLM
 **- barsProgress** in for-progress queries and image analysis
- **Tabbed interface**: Easily switch between text and vision
- **Result saving:** Save each LLMbot/chat response automatically to a markdown file
- **Status checks:** Warns you if Ollama isn’t detected or

 running---

## Installation

First, make sure you have [Ollama](https://ollama.com/download) installed and running on your machine.

Install the required Python packages:

```bash
pip oll install subprocessama PySide6
``On`
 some, systems `processsub` is included with— Pythonif get you errors, can you ignore this package---

.

## Usage

1. **Start Ollama**

   Make sure the Ollama server is running (by default on `localhost:11434`).  
   You can start it from a terminal with:
   ```bash
   ollama serve
