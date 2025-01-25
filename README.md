
# SOFTDOC: Smart Documentation Assistant

SOFTDOC is an advanced AI-powered documentation assistant that utilizes Retrieval-Augmented Generation (RAG) with LangChain, LLaMA 2, and Nomic Embed Text. It offers real-time query resolution, contextual awareness, and seamless integration for document understanding.

---

## Features
- Advanced Retrieval-Augmented Generation (RAG) implementation.
- Powered by LLaMA 2 for language understanding.
- Nomic Embed Text for enhanced text embeddings.
- Streamlit-based interactive user interface.
- Fully server-based architecture using Ollama.

---

## Prerequisites

Before setting up the project, ensure you have the following installed:
- **Python** (3.8 or above)
- **Ollama** (to serve models like LLaMA 2 and Nomic Embed Text)
- **Git** (for cloning the repository)

---

## Getting Started

Follow these steps to set up and run SOFTDOC on your local machine:

### Step 1: Clone the Repository
Start by cloning the repository to your local machine:
```bash
git clone https://github.com/shreeramdrao/DocuSense.git
```

---

### Step 2: Install Ollama and Models
1. **Install Ollama**:
   Follow the official instructions to install Ollama on your system.
   
2. **Pull Required Models**:
   Use Ollama to download the necessary models:
   ```bash
   ollama pull llama2
   ollama pull nomic-embed-text
   ```

---

### Step 3: Set Up the Virtual Environment
Navigate to the cloned repository and create a virtual environment:
```bash
cd DocuSense
python -m venv venv
```

Activate the virtual environment:
- **Linux/MacOS**:
  ```bash
  source venv/bin/activate
  ```
- **Windows**:
  ```bash
  venv\Scripts\activate
  ```

---

### Step 4: Install Dependencies
Install all required Python libraries by running:
```bash
pip install -r requirements.txt
```

---

### Step 5: Run the Application
Launch the Streamlit application:
```bash
streamlit run DocuSense_app.py
```

This will start the SOFTDOC application, and you can access it via the local Streamlit URL displayed in your terminal.

---

## Directory Structure
```
DocuSense/
├── models/                 # Folder for external models (handled by Ollama)
├── src/                    # Source code for application logic
├── requirements.txt        # Python dependencies
├── DocuSense_app.py        # Main application file
├── README.md               # Project documentation
└── venv/                   # Virtual environment (after setup)
```

---

## How It Works
1. **Advanced RAG**: Uses LangChain to implement RAG for smarter document search and query resolution.
2. **LLaMA 2**: Serves as the language backbone for processing queries.
3. **Nomic Embed Text**: Handles embedding text for efficient vector searches.
4. **Streamlit**: Provides an interactive and user-friendly application interface.

---

## Contributing
Feel free to open issues or submit pull requests for enhancements, bug fixes, or additional features.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Support
For any issues or questions, contact [Shreerama D S](mailto:your-email@example.com) or open an issue in the repository.
