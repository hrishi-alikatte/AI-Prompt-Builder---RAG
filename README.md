# 🧩 Prompt Engineering: Customizable AI Prompt Generator

## 📌 Overview

This project implements a **prompt engineering system** that automatically creates, customizes, and enhances AI prompts using a **Retrieval-Augmented Generation (RAG)** approach. By combining **semantic search** and **small language models**, the system efficiently generates optimized prompts tailored to user queries. The project leverages the "awesome-chatgpt-prompts" repository and enhances the prompts using models like **TinyLlama** and **Phi-2**.

## 🚀 Key Features

- 🔍 **Vector Database of Prompts**: Build a vector database from the "awesome-chatgpt-prompts" repository for easy retrieval.
- 🔎 **Semantic Search**: Use semantic search to find the most relevant prompts based on user queries.
- 📊 **Pattern Analysis**: Analyze and extract patterns from similar prompts to improve customization.
- ✍️ **Prompt Generation**: Automatically generate customized prompts tailored to user requests.
- 🚀 **Prompt Enhancement**: Utilize small language models (TinyLlama, Phi-2) to enhance and refine prompts.

  ##
  <img width="829" alt="Screenshot 2025-04-14 at 3 19 12 PM" src="https://github.com/user-attachments/assets/f5b43fbb-3e31-4ad0-a072-a382f109e8ca" />


## 🛠️ Technologies Used

- **Sentence Transformers**: For embedding generation and creating semantic vector representations of prompts.
- **Milvus (via Zilliz Cloud)**: For efficient vector storage and retrieval of prompt data.
- **Hugging Face Transformers**: For enhancing prompts using advanced language models.
- **Gradio**: For building a simple user interface for easy interaction with the system.

## ⚙️ Workflow

1. **Semantic Search**: The system finds semantically similar prompts based on the user's query.
2. **Pattern Extraction**: Analyze the retrieved prompts to extract patterns, roles, and instructions.
3. **Best Match Selection**: Identify the best prompt match based on term overlap and relevance.
4. **Base Prompt Generation**: Generate a base prompt from the best match found during the search.
5. **Prompt Enhancement**: Enhance the generated prompt using small language models like TinyLlama and Phi-2 for better customization.

## 📁 Project Structure

## 🛠️ Installation

To get started, clone the repository and install the dependencies:

1. Clone the repository:

```bash
git clone https://github.com/your-username/prompt-engineering.git
cd prompt-engineering
```

## Install the required dependencies:
pip install -r requirements.txt
Set up Milvus for vector storage (refer to the data/ directory for setup instructions).
🧑‍💻 How to Use

1. Generate Embeddings
Use the scripts/generate_embeddings.py script to process prompts and create embeddings using Sentence Transformers.
Example command:
python scripts/generate_embeddings.py --input_file data/prompts.json
2. Run Semantic Search
Perform a semantic search using the scripts/semantic_search.py script to find the most relevant prompts based on a user query.
Example command:
python scripts/semantic_search.py --query "How to improve my writing skills?"
3. Generate and Enhance Prompts
Run the scripts/generate_prompt.py script to create and enhance prompts.
Example command:
python scripts/generate_prompt
You said:
in a single clipboard!!!
ChatGPT said:
Here’s the full content for your README.md file, ready to be copied and pasted in one go:
## 📁 Project Structure

prompt-engineering/ ├── data/ # Data storage for prompt vector database ├── scripts/ # Scripts for semantic search, analysis, and prompt generation ├── models/ # Pretrained models for prompt enhancement (TinyLlama, Phi-2) ├── app/ # User interface built with Gradio ├── requirements.txt # Python dependencies └── README.md # Project documentation

## Install the required dependencies:
pip install -r requirements.txt
Set up Milvus for vector storage (refer to the data/ directory for setup instructions).
🧑‍💻 How to Use

1. Generate Embeddings
Use the scripts/generate_embeddings.py script to process prompts and create embeddings using Sentence Transformers.
Example command:
python scripts/generate_embeddings.py --input_file data/prompts.json
2. Run Semantic Search
Perform a semantic search using the scripts/semantic_search.py script to find the most relevant prompts based on a user query.
Example command:
python scripts/semantic_search.py --query "How to improve my writing skills?"
3. Generate and Enhance Prompts
Run the scripts/generate_prompt.py script to create and enhance prompts.
Example command:
python scripts/generate_prompt.py --query "Write a creative story about a lost traveler."
4. Web Demo (Optional)
To interact with the system via a web interface, run the Gradio app:
streamlit run app/app.py
🎯 Example

Input Query: "How to improve my writing skills?"
Generated Prompt:
"Write a detailed guide on improving writing skills, focusing on techniques for creativity, sentence structure, and engaging storytelling."
Enhanced Prompt:
"Generate a comprehensive tutorial for aspiring writers. Include tips on brainstorming ideas, using vivid language, crafting compelling plots, and overcoming writer's block."
🔧 Dependencies

Python 3.7+
Sentence Transformers (sentence-transformers)
Milvus (pymilvus)
Hugging Face Transformers (transformers)
Gradio (gradio)
Streamlit (for web interface)
Install the dependencies using:
pip install -r requirements.txt
⚡ Contributing

We welcome contributions! If you'd like to contribute:
Fork the repository
Create a new branch (git checkout -b feature-branch)
Make your changes
Commit your changes (git commit -am 'Add new feature')
Push to the branch (git push origin feature-branch)
Create a pull request

📝 License

This project is licensed under the MIT License - see the LICENSE file for details.



