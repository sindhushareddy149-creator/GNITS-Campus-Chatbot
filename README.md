GNITS Campus Information Chatbot
An AI-powered campus information assistant designed to help freshers,
students, and visitors find information about college rules, events,
clubs, locations, facilities, and procedures.
Project Overview
The GNITS Campus Information Chatbot aims to provide quick answers to
common campus-related questions, such as:
- Where is the placement cell?
- How can I join a student club?
- What facilities are available on campus?
- Where can I find information about college procedures and events?
The project focuses on campus-specific knowledge management,
conversational AI, information retrieval, and student-service
automation.
Problem Statement
Students and visitors often need to search across multiple sources to
find accurate campus information. This chatbot is intended to make that
information easier to access through a conversational interface.
Project Scope
The project brief describes an Essential (Track A) implementation
focused on core campus information processing and query answering.

The proposed information sources include:
- College handbooks and documents
- College website content
- Event calendars and updates
- Club information
- Contact directories
- Campus location and facility information
Update this list to include only the sources that are actually
connected in the current implementation.

Technology Stack
The project context identifies the following technologies:
- Python -- application development
- Streamlit -- user interface
- LangChain -- language-model application and retrieval workflow
- FAISS -- vector similarity search
- Hugging Face -- model and/or embedding ecosystem
Confirm the exact models, embedding model, libraries, and versions
used before publishing a final technical inventory.

How It Works
At a high level, a campus information assistant based on
retrieval-augmented generation (RAG) can follow this workflow:
1. Collect the campus documents and other supported information
   sources.
2. Process the content into smaller text chunks.
3. Generate embeddings for the processed content.
4. Store and search the embeddings using a vector index.
5. Retrieve relevant content when a user submits a question.
6. Use the retrieved context to help generate a response.
This describes the general RAG workflow. Adjust it to match the exact
pipeline implemented in this repository.

Features
The project brief identifies these intended capabilities:
- Conversational answers to campus-related questions
- Access to information about college rules and procedures
- Information about clubs and events
- Guidance about campus locations and facilities
- Retrieval of information from campus-specific content

