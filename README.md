### SEC Filing Analysis

**Description:**
This project analyzes SEC filings to extract key information, summarize content, and evaluate the effectiveness of different NLP techniques.

**Key Features:**
- **Data Fetching:** Retrieves SEC filings using the CIK (Central Index Key) of companies.
- **Text Extraction:** Extracts relevant text from filings using BeautifulSoup and regular expressions.
- **Summarization:** Implements both traditional (LSA) and modern (DistilBART) summarization techniques.
- **Keyword Extraction:** Uses TF-IDF and KeyBERT for keyword extraction.
- **Evaluation:** Calculates ROUGE scores, semantic similarity, and keyword relevance metrics.

**Setup:**
1. **Environment:** Python 3.x with libraries like Requests, BeautifulSoup, NLTK, Sumy, Transformers, KeyBERT, Scikit-learn, and SentenceTransformers.
2. **Data:** Access SEC filings through the provided API or similar data sources.
3. **Execution:** Run the notebook to fetch, process, and analyze SEC filings.

**How to Use:**
- Define the CIK for the company you want to analyze.
- Fetch and process the SEC filings.
- Use the provided functions to summarize text, extract keywords, and evaluate results.

**Contributing:**
- Contributions to improve data fetching, add new analysis techniques, or enhance evaluation metrics are welcome. Please fork and submit pull requests.

**License:**
- This project is licensed under the MIT License.