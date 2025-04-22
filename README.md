# Generative-AI-Chatbot
This project demonstrates the use of Generative AI to build a functional chatbot tailored for banking and financial services.

## Overview
The goal of this project is to design and implement a Generative AI-powered chatbot using Python, capable of automating specific banking services. By selecting a targeted financial domain—such as account inquiries, loan assistance, investment advice, or fraud detection—the chatbot aims to simulate intelligent conversations, provide instant support, and showcase the practical benefits of AI in enhancing customer engagement and operational efficiency.

## Methodology
This project developed a Loan Assistance Chatbot named MoneyWise's Alex using Generative AI techniques and Python. The chatbot integrates multiple components to deliver intelligent, secure, and user-friendly loan support:

- Initial Greeting: Welcomes users and introduces available services.

- Prompt Injection Detection: Secures the chatbot from malicious input manipulation.

- User Intent Identification: Categorizes user queries to provide relevant responses.

- Sentiment Analysis: Analyzes feedback and tailors responses based on sentiment type.

- Retrieval-Augmented Generation (RAG): Enhances responses by pulling context from external documents using embeddings and vector search.

- Response Generation: Constructs final responses based on the processed input, sentiment, and retrieved knowledge.

The system was developed using LangChain, OpenAI's GPT models, Gradio for UI, and document retrievers like FAISS to deliver an interactive and intelligent user experience.

## Conclusion
The chatbot demonstrates how Generative AI can enhance banking customer service by automating complex interactions with contextual, document-backed responses. It successfully provides loan-related information while implementing robust security measures against prompt injection, data leaks, and input manipulation. The integration of RAG, sentiment analysis, and intent detection results in an explainable, adaptive system that improves customer experience and operational efficiency in the banking sector. This project showcases the practical impact of AI-powered automation in delivering secure and scalable financial services.
