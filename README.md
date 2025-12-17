# EEEVA
EEEVA — ELECTRICAL AND ELECTRONICS ENGINEERING VIRTUAL ASSISTANT

Overview:
EEEVA is a hybrid, tool-augmented academic chatbot designed to address information silos in university environments. Academic data is commonly distributed across PDFs, Word documents, spreadsheets, and databases, making retrieval slow and error-prone. EEEVA provides a single conversational interface that allows faculty to securely retrieve academic information using natural language queries.

Problem Statement:
Universities store critical academic information across disconnected sources, including:
PDF syllabi and scanned documents
DOCX lab manuals and official notices
CSV timetables and attendance records
XLSX inventories and administrative data
This fragmentation forces users to manually search across multiple systems, leading to inefficiency, duplicated effort, and inconsistent access to information.

Solution:
EEEVA integrates a chat-based frontend with a tool-aware backend that dynamically retrieves data from both structured and unstructured sources. Rather than relying solely on language model generation, EEEVA performs explicit data retrieval and tool execution before generating responses, improving accuracy, reliability, and trustworthiness.

Key Features:
1.Natural language academic queries
2. Multi-format document handling (PDF, DOCX, CSV, XLSX)
3. Tool-augmented responses to reduce hallucinations
4. Modular and extensible system architecture
5. Scalable design suitable for institutional expansion

System Architecture:
Frontend: Next.js–based conversational interface
Backend: FastAPI service layer for request routing and tool execution
AI Layer: LLM-based intent understanding and response synthesis
Data Layer: Structured and unstructured academic data sources

Tech Stack:
Frontend: Next.js, React
Backend: FastAPI, Python
AI / NLP: LLM-based reasoning with tool augmentation (Ollama)
Data Handling: PDF, DOCX, CSV, XLSX processing

Project Status:
This repository presents the conceptual design and system overview of EEEVA. The implementation is under active development and is not publicly released.

Disclaimer:
EEEVA is an academic and research project. Any real-world deployment must comply with institutional data privacy and security regulations.
