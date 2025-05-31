# ⚖️ Legal RAG System | 🐍 Python + 🧠 LangChain  

> **An Intelligent Legal Assistant powered by Retrieval-Augmented Generation (RAG)**  
> _“Transforming legal research and contract analysis with AI”_

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![LangChain](https://img.shields.io/badge/LangChain-%F0%9F%91%93-purple)
![ChromaDB](https://img.shields.io/badge/ChromaDB-VectorDB-green)
![License](https://img.shields.io/badge/License-MIT-brightgreen)
![Status](https://img.shields.io/badge/Status-Active-blue)

---

## 📘 Overview  
This project implements a **Retrieval-Augmented Generation (RAG)** system designed to process and analyze **legal documents**. By combining **large language models** with **intelligent retrieval**, the system can analyze NDAs, contracts, M&A agreements, and privacy policies — making legal insights more accessible and accurate.

---

## 💼 Business Value  

✨ The Legal RAG system brings immense value to:

- ⚡ **Faster Legal Research:** Quickly locate case laws, statutes, and clauses  
- 📜 **Smart Contract Analysis:** Extract obligations, terms, and risk factors  
- 📈 **Regulatory Monitoring:** Track compliance and detect changes in regulations  
- 🧠 **Informed Legal Decisions:** Use context-aware answers to guide legal strategy  

---

## 🔍 Key Use Cases  

- 🤖 **Legal Chatbots** – Ask legal questions and get AI-powered answers  
- 📑 **Contract Review Automation** – Extract terms & flag critical clauses  
- 🕵️‍♂️ **Regulatory Tracking** – Monitor laws, policies, and obligations  
- ⚖️ **Case Law Analysis** – Explore past judgments and references  
- 🧾 **Due Diligence** – Assess risks from contracts and M&A documents  

---

## 📂 Dataset  

The system uses curated datasets of real legal documents:

| Dataset       | Description                                           |
|---------------|-------------------------------------------------------|
| `contractnli` | NDAs and confidentiality agreements                   |
| `cuad`        | Contracts annotated with legal clauses                |
| `maud`        | Merger & Acquisition contracts                        |
| `privacy_qa`  | Q&A data from real-world privacy policies             |

---

## 🗂️ Project Structure  

```
├── RAG_Assg_Legal_Documents_Starter.ipynb    # Main notebook
├── rag_legal/
│   ├── corpus/
│   │   ├── contractnli/                      # NDAs
│   │   ├── cuad/                             # Clause annotations
│   │   ├── maud/                             # M&A contracts
│   │   └── privacy_qa/                       # Privacy policies
│   └── benchmark/                            # Evaluation data
│       ├── contractnli.json
│       ├── cuad.json
│       ├── maud.json
│       └── privacy_qa.json
└── requirements.txt                          # Python dependencies
```

---

## 🛠️ Implementation Details  

1. 📥 **Load & Preprocess** – Clean and structure legal texts  
2. ✂️ **Chunk Documents** – Break long texts into retrieval-friendly chunks  
3. 🧬 **Generate Embeddings** – Transform text into vector space  
4. 🗃️ **Vector DB** – Store embeddings in ChromaDB  
5. 🔗 **RAG Pipeline** – Combine retrieval with LLM for accurate responses  
6. 📊 **Evaluate** – Score performance using legal metrics with RAGAS  

---

## 🧰 Tech Stack  

| Tool          | Purpose                            |
|---------------|------------------------------------|
| `LangChain`   | LLM app orchestration              |
| `ChromaDB`    | Vector-based semantic search       |
| `NLTK`        | Text preprocessing                 |
| `Pandas`      | Data manipulation                  |
| `RAGAS`       | RAG system evaluation              |
| `Seaborn`     | Visualizations                     |
| `Matplotlib`  | Charts and graphs                  |

---

## 🚀 Getting Started  

### 🧾 Clone the Repo  
```bash
git clone https://github.com/your-username/legal-rag-system.git
cd legal-rag-system
```

### 📦 Install Dependencies  
```bash
pip install -r requirements.txt
```

### 🧪 Run the Notebook  
```bash
jupyter notebook RAG_Assg_Legal_Documents_Starter.ipynb
```

Follow the steps in the notebook to build and test the system.

---

## 📋 Requirements  

```txt
langchain-openai  
langchain-community  
langchain-chroma  
datasets  
ragas  
rouge_score  
matplotlib  
seaborn  
pandas  
nltk  
```

---

## 📜 License  
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments  
- 🤝 Thanks to the LangChain community  
- 📚 Contributors of the open-source legal datasets  
- 🛠️ Developers of the Python libraries powering this system  

---

## 👨‍⚖️ Let AI Be Your Legal Assistant  
> Ready to rethink legal analysis with RAG and AI? Clone the repo and explore now!
