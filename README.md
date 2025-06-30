# 🧠 Expert Knowledge Worker (RAG-Powered AI Assistant)

The **Expert Knowledge Worker** is an AI-powered assistant built using **Retrieval-Augmented Generation (RAG)** that serves as an internal expert on all company-related matters. Designed to work with both **local** and **cloud-based** language models, this assistant retrieves context from internal documents and delivers accurate, context-aware answers—making it an ideal tool for employees, clients, and business processes.

---

## 🚀 Project Highlights

* ✅ Built using **LangChain** to manage document loading, embedding, retrieval, and response generation
* ✅ Integrated with **Ollama** (to run local LLMs like LLaMA, Mistral) for offline/private model use
* ✅ Also supports **OpenAI API** (GPT-3.5 / GPT-4) for cloud-based inference
* ✅ Uses **Retrieval-Augmented Generation (RAG)** to search internal knowledge before generating answers
* ✅ Developed and tested in **Jupyter Lab** for iterative development and demonstration and Gradio for a live UI demo

---

## 🔍 Use Case

Think of this as your organization’s **internal ChatGPT**, fine-tuned on your:

* 📝 Policy documents
* 📦 Product documentation
* 🤝 Client FAQs
* 🧾 HR materials
* 📁 Internal training content

It’s ideal for:

* New employee onboarding
* Customer support automation
* Internal knowledge access
* Business decision support
* and many more use cases.....
---

## 🛠️ Technologies Used

| Technology         | Purpose                                       |
| ------------------ | --------------------------------------------- |
| **LangChain**      | Orchestrates components of the RAG pipeline   |
| **Ollama**         | Runs local LLMs for private inference         |
| **OpenAI API**     | Accesses GPT-4 for cloud inference            |
| **RAG**            | Provides context-aware and accurate answers   |
| **FAISS / Chroma** | Vector search for retrieving relevant content |
| **Jupyter Lab**    | Interactive environment for development       |

---

## 🧪 How It Works

1. **Load Data**: Upload PDFs, docs, or text files containing internal knowledge.
2. **Embed Documents**: Generate vector embeddings using `OpenAIEmbeddings` or other supported models.
3. **Store & Retrieve**: Save embeddings in **FAISS** or **Chroma** vector databases.
4. **Ask Questions**: Query the assistant; it fetches relevant context and generates a well-informed answer.
5. **Switch Models**: Run locally via Ollama or switch to OpenAI API easily.

---


## 🔧 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Aryan-any/Expert-Knowledge-Worker.git
cd Expert-Knowledge-Worker
```

### 2. Create a Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Set up OpenAI API Key (if using OpenAI)

```bash
export OPENAI_API_KEY=your_key_here  # On Windows: set OPENAI_API_KEY=your_key_here
```

### 5. Run via Jupyter Lab

```bash
jupyter lab
```

Open the notebook in `/notebooks` and follow instructions to load data, create embeddings, and ask questions.

---

## 📌 Notes

* For **Ollama**, make sure it is installed and running on your system: [https://ollama.com](https://ollama.com)
* You can switch between models easily inside the notebook or script (OpenAI ↔ Ollama)
* Document formats supported: `.pdf`, `.txt`, `.md`, `.docx`

---

## 💡 Future Work

* Deploy as a web app (Streamlit or Flask)
* Add document upload UI
* Add memory & chat history
* Fine-tuning and multi-language support

---

## 🤝 Contribution

Feel free to fork, improve, or suggest new features! Pull requests and issues are always welcome.

---

## 📬 Contact

Built with 🔍 and ❤️ by **Aryan Mishra**
📧 *[mishraaryanm@gmail.com](mailto:mishraaryanm@gmail.com)*

---


