# SIT Open Day RAG Chatbot

**Current status: Work in progress**

I am developing this chatbot to investigate whether Retrieval-Augmented Generation (RAG) can improve answers to questions about SIT courses, enrolment and Open Day information.

## Progress so far

I have completed the baseline testing stage. This involved:

- Testing Granite 3.3, Llama 3.1, Mistral and Qwen3
- Using zero-shot, persona and reasoning prompts
- Generating 300 baseline responses
- Evaluating the responses with BLEU, ROUGE-L and BERTScore
- Checking the responses for hallucinations against verified SIT information

I am now working on the RAG enhancement stage. The next step is to connect the models to the SIT information source and then compare the RAG results with the baseline results.

The completed baseline code and results will be added to this repository in separate stages as I review them.

## Main technologies

- Python
- LangChain
- Ollama
- FAISS
- Streamlit
- pytest

## Original project credit

I used the open-source [rag_chatbot](https://github.com/tschechlovdev/rag_chatbot) project by [tschechlovdev](https://github.com/tschechlovdev) as the starting foundation for this project.

The original Git history and MIT licence have been retained. My SIT-specific testing, evaluation and RAG development will be documented through my own commits.

## Author

Shreyas Patil

[GitHub profile](https://github.com/patilshreyas27)