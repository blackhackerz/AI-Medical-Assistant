# End-to-end-Medical-Chatbot-Generative-AI

# How to run?

### STEPS:

Clone the repository

```bash
Project repo: https://github.com/blackhackerz/AI-Medical-Assistant.git
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n medibot python=3.10 -y
```

```bash
conda activate medibot
```

### STEP 02- install the requirements

```bash
pip install -r requirements.txt
```

### Create a `.env` file in the root directory and add your Pinecone & openai credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxx"
GROQ_API_KEY = "xxxxxxxxxxxxxxxxxxxxx"
```

### Run the following command to store embeddings to pinecone

```bash

python store_index.py
```

### Finally run the following command

```bash
python app.py
```

### Now, open up localhost

```bash
https://localhost:8080
```

### Techstack Used:

- Python
- LangChain
- Flask
- GROQ
- Pinecone
