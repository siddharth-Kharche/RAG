# RAG: Retrieval-Augmented Generation Architectures

This repository provides a comprehensive collection of Retrieval-Augmented Generation (RAG) architectures, implemented as interactive Jupyter Notebooks. It is designed for AI practitioners, researchers, and developers interested in exploring, comparing, and building advanced RAG systems for context-aware, accurate, and intelligent AI applications[1][2][3].

---

## **Overview**

Retrieval-Augmented Generation (RAG) is a paradigm that enhances large language models (LLMs) by integrating information retrieval with generative capabilities. This approach enables LLMs to access external knowledge sources, improving the accuracy, relevance, and factuality of responses. The notebooks in this repository showcase a variety of RAG designs, each suited for different use cases and data types[2][3].

---

## **Included Architectures**

- **adaptive_rag.ipynb**: Demonstrates adaptive RAG techniques that dynamically adjust retrieval and generation strategies.
- **agentic_rag_using_deepseek_qdrant_and_langchain.ipynb**: Implements agentic RAG using DeepSeek, Qdrant vector database, and LangChain framework.
- **basic_agentic_rag.ipynb**: Introduces the fundamentals of agentic RAG, where agents specialize in different retrieval or reasoning tasks.
- **basic_unstructured_rag.ipynb**: Handles unstructured data (text, tables, images) for document retrieval and generation[3].
- **contextual_rag.ipynb**: Focuses on compressing retrieved documents to retain only the most relevant context for concise, accurate answers[3].
- **corrective_rag.ipynb**: Explores mechanisms for refining or correcting generated outputs using retrieved evidence.
- **fusion_rag.ipynb**: Implements query fusion and ranking (e.g., Reciprocal Rank Fusion) to combine multiple retrieval strategies for better results[3].
- **hybrid_rag.ipynb**: Combines vector search with traditional retrieval methods (like BM25) for improved relevance[3].
- **hyde_rag.ipynb**: Explores the "Hypothetical Document Embeddings" (HyDE) approach for retrieval.
- **naive_rag.ipynb**: A simple baseline combining document retrieval and generation[3].
- **parent_document_retriever.ipynb**: Demonstrates parent document retrieval for hierarchical or nested data.
- **rewrite_retrieve_read.ipynb**: Showcases advanced RAG workflows involving query rewriting and multi-step retrieval.
- **self_rag.ipynb**: Experiments with self-refining RAG systems.

---

## **Key Features**

- **Diverse RAG Architectures**: Explore naive, agentic, hybrid, fusion, contextual, and corrective RAG designs.
- **Hands-on Notebooks**: Each architecture is implemented as a Jupyter Notebook for easy experimentation and learning.
- **Modern Stack**: Utilizes frameworks like LangChain, vector databases (e.g., Qdrant, FAISS), and state-of-the-art LLMs (e.g., DeepSeek, Groq)[4][3].
- **Real-World Use Cases**: Examples include document Q&A, multi-modal retrieval, and domain-specific agentic solutions[2][3].

---

## **Getting Started**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/siddharth-Kharche/RAG.git
   cd RAG
   ```
2. **Install dependencies:**
   - Make sure you have Python 3.8+ and Jupyter Notebook installed.
   - Additional requirements will depend on the specific notebook (see notebook headers for details).

3. **Run the notebooks:**
   - Launch Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Open any notebook (e.g., `naive_rag.ipynb`) and follow the instructions inside.

---

## **Use Cases**

- **Conversational AI**: Build chatbots that can answer questions using external documents.
- **Knowledge Management**: Retrieve and generate insights from large unstructured datasets.
- **Multi-Agent Systems**: Deploy specialized agents for domain-specific retrieval and reasoning[2].

---

## **Contributing**

Contributions are welcome! Feel free to open issues, submit pull requests, or suggest new architectures and improvements.

---

## **Author**

**Siddharth Kharche**  
AI & ML Enthusiast | Generative AI | NLP | Computer Vision  
[LinkedIn](https://www.linkedin.com/in/siddharth-kharche-9a0681217) | [Medium](https://medium.com/@siddharthkharche)

---

## **Acknowledgments**

- Inspired by the latest advancements in RAG, LLMs, and open-source AI communities.
- Special thanks to Krish Naik and Sunny Savita for educational content on RAG[3].

---

## **License**

This repository is open-source. See the LICENSE file for details.

---

> For more details and updates, visit the [GitHub repository](https://github.com/siddharth-Kharche/RAG)[1][2][3].

---

**#RAG #RetrievalAugmentedGeneration #AI #LLM #OpenSource #LangChain #Qdrant #epSeek #Groq

[1] https://github.com/siddharth-Kharche/RAG
[2] https://www.linkedin.com/posts/siddharth-kharche-9a0681217_ai-rag-retrievalaugmentedgeneration-activity-7289341396996513792-JfJZ
[3] https://www.linkedin.com/posts/siddharth-kharche-9a0681217_ai-artificialintelligence-genai-activity-7287376661749125120-jtPr
[4] https://github.com/siddharth-Kharche/-RAG-system-powered-by-deepseek-r1
[5] https://github.com/siddharth-Kharche
[6] https://github.com/siddharth-Kharche/NLP
[7] https://github.com/siddharth-Kharche/Feature-Engineering-in-machine-Learning/actions
[8] https://github.com/siddharth-nandagopal/retail-rag
[9] https://www.youtube.com/watch?v=3kfUmxFyuPA
[10] https://intellabs.github.io/RAGFoundry/
[11] https://dev.to/spara_50/rag-step-by-step-open-source-edition-330g
