# LangChain Synthetic Data Tutorial

This project demonstrates how to use **LangChain** in combination with **OpenAI** to create synthetic datasets.  
It is based on a Python tutorial implemented in a Jupyter Notebook, walking you step-by-step through creating a data model, defining prompt templates, generating synthetic data, and exporting it to CSV.

---

## 📌 Features

- **LangChain + OpenAI integration** for data generation
- Creation of **custom data models**
- Building **prompt templates** for synthetic data generation
- Developing a **data generator** using LangChain and OpenAI
- Generating synthetic data via the custom generator
- Exporting results to a **CSV file** for further use

---

## 🛠 Technologies Used

- [LangChain](https://www.langchain.com/)
- [OpenAI API](https://platform.openai.com/)
- [Pandas](https://pandas.pydata.org/)
- [Jupyter Notebook](https://jupyter.org/)

---

## 📦 Installation

1. **Clone the repository**
    ```bash
    git clone https://github.com/keanaido19/langchain-synthetic_data_tutorial.git
    cd langchain-synthetic_data_tutorial
    ```
2. **Create a virtual environment**
    ```bash
    python -m venv venv
    source venv/bin/activate   # Mac/Linux
    venv\Scripts\activate      # Windows
    ```
3. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```
---

## ⚙️ Configuration

1. **Create a ```.env``` file in the project root:**
    ```dotenv
    OPENAI_API_KEY=your_api_key_here
    ```

2. **You can obtain an API key from the [OpenAI dashboard](https://platform.openai.com/account/api-keys).**

---

## 🚀 Usage

1. **Launch Jupyter Notebook**
    ```bash
    jupyter notebook
    ```
2. **Open the tutorial notebook:**
    ```
   langchain_synthetic_data_tutorial.ipynb
   ```
3. **Follow the steps in the notebook to:**

    * Define your data model

    * Create prompt templates

    * Build and run the data generator

    * Export generated data to CSV