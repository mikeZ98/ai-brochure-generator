# 🧠 AI Brochure Generator

**AI-powered tool that scrapes a company website and generates a professional marketing brochure using LLMs (Large Language Models).**  
Built during an advanced LLM Engineering course as a showcase project.

---

## 🚀 Project Overview

This tool visits a company website, scrapes all relevant content using Selenium and BeautifulSoup, then analyzes the data with GPT-4o to generate a **beautiful markdown-based brochure** in Polish.

It combines automation, web scraping, and generative AI – simulating how a human marketer would explore and present a company.

---

## 🛠️ Tech Stack

- 🧠 `OpenAI GPT-4o` – natural language generation
- 🌐 `Selenium` – dynamic webpage scraping
- 🧼 `BeautifulSoup` – HTML parsing and cleanup
- 🔗 `Lang-style prompts` – used for system prompting and filtering
- 📦 `Python`, `dotenv`, `requests`, `IPython Markdown display`

---

## 📦 Features

- ✅ Headless browser scraping (JS-rendered pages supported)
- ✅ Automatic link filtering (e.g. About, Careers, Innovation, etc.)
- ✅ LLM prompt-based markdown generation (in Polish 🇵🇱)
- ✅ Optional streaming markdown output

---

## 📸 Demo

### Example input:
> URL: https://openai.com/

### Output:
![Screenshot](./examples/sample_output.png)  
📄 Full brochure in markdown based on site content – formatted like a PDF.

---

## 📂 Repository Structure

```bash
ai-brochure-generator/
├── ai-brochure-generator.ipynb     # Main Jupyter Notebook
├── README.md                       # Project overview
├── LICENSE                         # MIT License
├── .gitignore                      # Files to ignore
└── examples/
    └── sample_output.md            # Example output
```

## 🧠 Why This Project?

Built during an LLM engineering course to showcase:

- How to combine **web scraping + LLMs**
- Prompt engineering (*multi-shot, chain-of-thought*)
- Realistic use case of automating **business document generation**
- Designed to simulate tasks performed by junior–mid AI engineers in real-world projects

---

## 🪪 License

MIT – free to use, modify, and share ✌️
