# Legal RAG System | Python | LangChain #

## Overview  
This project implements a Retrieval-Augmented Generation (RAG) system designed specifically for processing and analyzing legal documents. The system enhances information extraction from various legal agreements including NDAs, contracts, merger/acquisition agreements, and privacy policies by combining the power of large language models with a specialized retrieval mechanism.

## Business Value  
The RAG system for legal documents provides significant value for businesses, law firms, and regulatory bodies:

- **Faster Legal Research:** Reduce time spent searching for relevant case laws, precedents, statutes, or contract clauses  
- **Improved Contract Analysis:** Automatically extract key terms, obligations, and risks from lengthy contracts  
- **Regulatory Compliance Monitoring:** Stay updated with legal and regulatory changes by retrieving relevant legal updates  
- **Enhanced Decision-Making:** Provide accurate and context-aware legal insights for risk assessment and legal strategy  

## Key Use Cases  
- Legal Chatbots  
- Contract Review Automation  
- Tracking Regulatory Changes and Compliance Monitoring  
- Case Law Analysis of Past Judgments  
- Due Diligence & Risk Assessment  

## Dataset  
The project utilizes a specialized legal document dataset containing:

- **contractnli:** Various non-disclosure and confidentiality agreements  
- **cuad:** Contracts with annotated legal clauses  
- **maud:** Various merger/acquisition contracts and agreements  
- **privacy_qa:** A question-answering dataset containing privacy policies  

## Project Structure  
```
├── RAG_Assg_Legal_Documents_Starter.ipynb   # Main notebook with implementation  
├── rag_legal/
│   ├── corpus/                              # Legal document corpus  
│   │   ├── contractnli/                     # NDA and confidentiality agreements  
│   │   ├── cuad/                            # Annotated contracts  
│   │   ├── maud/                            # Merger/acquisition agreements  
│   │   └── privacy_qa/                      # Privacy policies  
│   └── benchmark/                           # Evaluation files  
│       ├── contractnli.json  
│       ├── cuad.json  
│       ├── maud.json  
│       └── privacy_qa.json  
└── requirements.txt                         # Project dependencies  
```

## Implementation Details  
The implementation follows these key steps:

1. **Data Loading & Preprocessing:** Loading legal documents and preparing them for analysis  
2. **Document Chunking:** Splitting documents into manageable chunks for efficient retrieval  
3. **Embedding Generation:** Creating vector representations of document chunks  
4. **Vector Store Creation:** Building a searchable database of document embeddings  
5. **RAG Pipeline Construction:** Implementing the retrieval and generation components  
6. **Evaluation:** Assessing system performance using specialized legal metrics  

## Technologies Used  
- **LangChain:** Framework for building LLM applications  
- **ChromaDB:** Vector database for efficient similarity search  
- **NLTK:** Natural language processing toolkit for text preprocessing  
- **Matplotlib/Seaborn:** Data visualization libraries  
- **Pandas:** Data manipulation and analysis  
- **RAGAS:** Evaluation framework for RAG systems  

## Getting Started  

### Clone this repository  
```bash
git clone <your-repo-url>
cd <your-repo-directory>
```

### Install the required dependencies  
```bash
pip install -r requirements.txt
```

### Run the project  
Open the Jupyter notebook:
```bash
jupyter notebook RAG_Assg_Legal_Documents_Starter.ipynb
```

Follow the step-by-step implementation and analysis in the notebook.

## Requirements  
```bash
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

## License  
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
