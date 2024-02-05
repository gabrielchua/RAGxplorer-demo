# RAGxplorer Demo 🦙🦺

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://ragxplorer.streamlit.app/)

View the RAGxplorer project [here](https://github.com/gabrielchua/RAGxplorer/).

# Installation 
**Installation**

To run RAGxplorer, ensure you have Python installed, and then install the necessary dependencies:

```bash
pip install -r requirements.txt
```

**Usage**

1. Setup `OPENAI_API_KEY` (optional, to use OpenAI embedding models and advanced retrival techniques) and `HF_API_KEY` (optional, to use HF embedding models). Copy
    the `.streamlit/secrets.example.toml` file to `.streamlit/secrets.toml` and fill in the values.
2. To start the application, run:
    ```bash
    streamlit run app.py
    ```

**Docker 🐳**

To run the project using Docker, run the following command:

```bash
docker-compose up -d
```
