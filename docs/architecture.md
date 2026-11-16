# Target architecture

The planned request flow is:

```text
Streamlit → FastAPI → RAG Pipeline → Qwen API / Vector Store
```

Streamlit will provide the user interface. FastAPI will expose the application API. The RAG pipeline is intended to coordinate document processing, semantic retrieval, and answer generation through the Qwen API and a vector store.

This is a target design only. None of these components or integrations has been implemented yet.
