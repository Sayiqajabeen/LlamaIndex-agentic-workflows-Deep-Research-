# LlamaIndex-agentic-workflows-Deep-Research- 

# 🦙 LlamaIndex Agentic Workflows – Deep Research

This project demonstrates how to build **agentic workflows** using [LlamaIndex](https://github.com/jerryjliu/llama_index), enabling autonomous and tool-augmented agents for deep research tasks. The notebook has been converted into a standalone Python script for easy integration and deployment.

---

## 📌 Key Features

- 🔧 **LlamaIndex Agent Integration** – Build and manage autonomous agents  
- 🔍 **Tool Usage** – Web search, summarization, and knowledge retrieval  
- 🔁 **Multi-Step Reasoning** – Agent chains for in-depth analysis  
- 🤖 **OpenAI LLM Integration** – Use GPT-powered reasoning in research workflows  

---

## 🗂️ Project Structure

```bash
llamaindex-agentic-workflows/
├── llamaindex_agentic_workflows.py   # Main Python script (converted from notebook)
├── README.md                         # Project description and usage guide
├── requirements.txt                  # Dependencies (see below)

## 🚀 Setup Instructions
## 1. Clone this repository
   git clone https://github.com/your-username/llamaindex-agentic-workflows.git
   cd llamaindex-agentic-workflows

## 2. Create a virtual environment
  python -m venv venv
  source venv/bin/activate  # On Windows: venv\Scripts\activate

## 3. Install dependencies
   pip install -r requirements.txt

## 4. Set your OpenAI API key
   Create a .env file in the root directory:
   OPENAI_API_KEY=your_openai_key_here

## 🧠 Usage
  Run the Python script:
  python llamaindex_agentic_workflows.py

## 📦 Requirements
  Here's what you'll need (already included in requirements.txt):
  llama-index
  openai
  pandas
  matplotlib
  python-dotenv

## 🧰 Tech Stack

 | Layer                  | Technology / Library         | Purpose                                                                 |
 |------------------------|------------------------------|-------------------------------------------------------------------------|
 | **Language**           | Python 3.x                   | Core programming language                                               |
 | **LLM Backend**        | OpenAI GPT (`openai` package)| Powers the agent's reasoning and generation                             |
 | **Agentic Framework**  | LlamaIndex                   | Agent orchestration, memory, and tool integration                       |
 | **Env Management**     | python-dotenv                | Loads API keys securely from a `.env` file                              |
 | **Data Handling**      | pandas                       | Data manipulation and structured outputs                                |
 | **Visualization**      | matplotlib                   | For generating plots or charts (if applicable)                          |
 | **Deve Interface**     | Jupyter Notebook             | Initial format for interactive coding (converted to `.py` script)       |
 | **Package Management** | pip                          | Installs all required Python libraries                                  |




## 🙏 Acknowledgements
  LlamaIndex for the agentic framework
  OpenAI for LLM APIs






