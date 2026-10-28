# RegAssist: Regulatory Compliance Verification Using RAG

## 📌 About

RegAssist is a Retrieval-Augmented Generation (RAG) system designed to help supervisors verify compliance findings using regulatory documents issued by Bangladesh Bank. It retrieves relevant regulatory evidence and generates answers with source references to support human decision-making.

## ✨ Key Features

- **Hybrid Search:** Combines dense retrieval and BM25 keyword search.
- **Improved Retrieval:** Uses Reciprocal Rank Fusion (RRF), metadata-aware scoring, and Cross-Encoder reranking.
- **Regulatory Supersession Control:** Helps identify applicable regulatory provisions.
- **Source References:** Provides regulatory details such as circular number, issue date, section, and page.
- **Human-in-the-Loop:** Supports supervisors without replacing their final judgment.

## ⚙️ How It Works

1. Loads and processes regulatory documents.
2. Retrieves relevant passages using hybrid search.
3. Combines and reranks the retrieved results.
4. Identifies applicable regulatory evidence.
5. Generates answers with source references.
6. Displays the responses through a Gradio interface.

## 📊 Evaluation

RegAssist was evaluated using **102 regulatory verification queries** covering payment systems, monetary policy, and foreign exchange.

- Semantic similarity: **74.08%**
- Numerical accuracy: **80.24%**
- Responses rated at least Useful by Supervisor 1: **99.0%**
- Responses rated at least Useful by Supervisor 2: **99.0%**

## 🛠️ Technology Stack

- Python
- Google Colab
- Gradio
- Retrieval-Augmented Generation (RAG)
- Dense and BM25 retrieval
- Cross-Encoder reranking

## 🚀 Getting Started

1. Open the project notebook in Google Colab.
2. Install the required dependencies.
3. Configure the required model credentials.
4. Load the authorized regulatory documents.
5. Run the notebook cells and launch the Gradio interface.





