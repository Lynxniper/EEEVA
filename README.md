# EEEVA
EEEVA — ELECTRICAL AND ELECTRONICS ENGINEERING VIRTUAL ASSISTANT

Overview:
EEEVA is a hybrid, tool-augmented academic chatbot designed to address information silos in university environments. Academic data is commonly distributed across PDFs, Word documents, spreadsheets, and databases, making retrieval slow and error-prone. EEEVA provides a single conversational interface that allows faculty to securely retrieve academic information using natural language queries.

Problem Statement:

Universities store critical academic information across disconnected sources, including:
1. PDF syllabi and scanned documents
2. DOCX lab manuals and official notices
3. CSV timetables and attendance records
4. XLSX inventories and administrative data

This fragmentation forces users to manually search across multiple systems, leading to inefficiency, duplicated effort, and inconsistent access to information.

Solution:
EEEVA integrates a chat-based frontend with a tool-aware backend that dynamically retrieves data from both structured and unstructured sources. Rather than relying solely on language model generation, EEEVA performs explicit data retrieval and tool execution before generating responses, improving accuracy, reliability, and trustworthiness.

Key Features:

1. Natural language academic queries
2. Multi-format document handling (PDF, DOCX, CSV, XLSX)
3. Tool-augmented responses to reduce hallucinations
4. Modular and extensible system architecture
5. Scalable design suitable for institutional expansion

System Architecture:

1. Frontend: Next.js–based conversational interface
2. Backend: FastAPI service layer for request routing and tool execution
3. AI Layer: LLM-based intent understanding and response synthesis
4. Data Layer: Structured and unstructured academic data sources

Tech Stack:

1. Frontend: Next.js, React
2. Backend: FastAPI, Python
3. AI / NLP: LLM-based reasoning with tool augmentation (Ollama)
4. Data Handling: PDF, DOCX, CSV, XLSX processing

Project Status:
This repository presents the conceptual design and system overview of EEEVA. The implementation is under active development and is not publicly released.

Disclaimer:
EEEVA is an academic and research project. Any real-world deployment must comply with institutional data privacy and security regulations.
