# LangChain Cookbook 🧠🍳

A hands-on collection of **modular Python examples** demonstrating key features and real-world applications of [LangChain](https://docs.langchain.com/).  
Each file is a standalone example—no complex setup required!

---

## 🔍 What is this?

This repository is a **cookbook-style reference** to help you:
- Learn LangChain concepts via **simple, focused code snippets**
- Explore integrations like **LLMs, vector stores, agents, tools, chains**, and more
- Quickly copy-paste working templates for your own AI projects

Whether you're a **beginner experimenting** or a **developer building production-grade AI**, this repo gives you clean examples to learn fast.

---

## 🧩 Structure

Each file shows one concept or use-case:

```
langchain-cookbook/
│
├── 00_llm_open_ai.ipynb            # Using OpenAI api as llm
├── 01_chatmodel_openai.ipynb       # ChatModel implementations using OpenAI 
├── 02_chatmodel_google.ipynb       # ChatModel implementations using Google gemini 
└── ... more coming!
```

---

## 📦 Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
```

Minimal dependencies—most examples use:
- [`langchain`](https://pypi.org/project/langchain/)
- [`openai`](https://pypi.org/project/openai/) or [`mistralai`](https://pypi.org/project/mistralai/)
- [`faiss-cpu`](https://pypi.org/project/faiss-cpu/)
- [`python-dotenv`](https://pypi.org/project/python-dotenv/) (for API keys)

---

## 🔐 API Keys (Optional)

Some examples require LLM providers like OpenAI or Mistral.

Create a `.env` file in the root:

```env
OPENAI_API_KEY=your_key_here
MISTRAL_API_KEY=your_key_here
```

---

## 🚧 Work in Progress

✅ Simple examples ready  
🧠 Advanced use-cases (multi-agent workflows, document QA pipelines, custom tools) coming soon!  
🌍 Contributions welcome – feel free to open an issue or PR!

---

## 📚 Resources

- [LangChain Docs](https://docs.langchain.com/)
- [LangChain GitHub](https://github.com/langchain-ai/langchain)
- [OpenAI API](https://platform.openai.com/)
- [Mistral](https://mistral.ai/)

---

## ⭐️ Support

If you find this repo helpful, give it a ⭐️ on GitHub and share it with fellow AI builders!

---

## License

MIT License © 2025 [Ujjwal Solanki](https://www.linkedin.com/in/ujjwalsolanki1)
