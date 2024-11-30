# Keyword-and-Semantic-Searches-with-ReRank


A modular Python application showcasing various search techniques using the Weaviate vector database and Cohere's reranking capabilities.

## Features

- **Dense Retrieval**: Implements vector-based semantic search with Weaviate.
- **Keyword Search**: Uses BM25-based traditional search methods.
- **ReRanking**: Enhances search results with Cohere's reranking model.
- **Output Options**: Provides both debug and user-friendly display formats.

---

## Getting Started

### Prerequisites

- Python 3.9 or higher
- Active Weaviate Cloud instance
- Cohere API key

### Installation

1. Clone the repository.

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt

3. 
Memory updated
Here is the rephrased and formatted README.md file:

markdown
Copy code
# Keyword + Dense Retrieval + ReRank

A modular Python application showcasing various search techniques using the Weaviate vector database and Cohere's reranking capabilities.

## Features

- **Dense Retrieval**: Implements vector-based semantic search with Weaviate.
- **Keyword Search**: Uses BM25-based traditional search methods.
- **ReRanking**: Enhances search results with Cohere's reranking model.
- **Output Options**: Provides both debug and user-friendly display formats.

---

## Getting Started

### Prerequisites

- Python 3.9 or higher
- Active Weaviate Cloud instance
- Cohere API key

### Installation

1. Clone the repository.

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a .env file in the root directory and add the following keys:

    ``` plaintext
    COHERE_API_KEY=your_cohere_key
    WEAVIATE_API_KEY=your_weaviate_key
    WEAVIATE_API_URL=your_weaviate_url
    ```

### Running the Application
Run the application using the following command:

```bash
python main.py
```

### API Keys
This application requires the following API keys:
- Cohere API Key
- Weaviate API Key
- Weaviate API URL
Store these keys in the .env file to keep them secure. Avoid committing the .env file to version control.
