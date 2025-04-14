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


