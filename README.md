# Cricket-ama
Ask me anything about cricket. I will try to answer it to the best of my knowledge.


[RAG(Retrieval Augmented Generation)](https://www.pinecone.io/learn/retrieval-augmented-generation/) is a technique in which we use powers of LLM to generate accurate information by grounding it with a known data source. This way we can leverage an LLM interface while avoiding hallucination . 
This notebook is an attempt to build a cricket ama interface using RAG.

# Data source
1. [pages-articles-multistream wiki dump](https://dumps.wikimedia.org/enwiki/latest/)

# Tech Stack
1. [Haystack](https://docs.haystack.deepset.ai/docs)
2. [Mistral-7B-Instruct-v0.1](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.1)


# Acknowlegement
This notebook is inspired from [mistral-haystack](https://github.com/anakin87/mistral-haystack) by [Stefano](https://github.com/anakin87).