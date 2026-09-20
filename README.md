# Taha Asif

Student Research Engineer at the [Centre for Assistive Technology Rhine-Ruhr (ZAT)](https://zat.nrw/). B.Sc. Infotronic Systems Engineering at [Rhine-Waal University of Applied Sciences](https://www.hochschule-rhein-waal.de/).

I work on assistive technology: software that adapts to the person using it. Most of my day is Python, Qt desktop applications, document parsing, and local LLM setups that keep data on the machine instead of sending it to an API.

Right now I'm building a reading support system for people with ADHD with researchers at ZAT. I handle the eye-tracking integration, the adaptive control logic, and the parsing pipelines that prepare documents for the model.

Our paper "ADHD by Design: Expert Co-Design and Prototype Development Towards a Pro-Adaptive Reading Support System" was presented at the MuC 2026 workshop "Towards Pro-Adaptivity in Human-Computer-Interaction" and is in press in the GI Digital Library.

## Projects

### [Movella DOT → LSL Pipeline](https://github.com/taaha17/movella-dot-lsl-pipeline)
Streams data from Movella Xsens DOT IMU sensors into Lab Streaming Layer, 16 channels per sensor at 30 Hz. Comes with terminal dashboards, bar viewers, and a 3D orientation viewer. I maintain it for the ZAT Rhine-Ruhr project.
`Python` · `BLE` · `Lab Streaming Layer` · `uv`

### [HSRW RAG Chatbot "Zero"](https://github.com/taaha17/hsrw-rag-chatbot)
Answers questions about university regulations without sending anything off the machine. Around 500 pages of PDFs go into a vector store, retrieval combines BM25 with semantic search, and an intent check routes queries before they reach the model.
`Python` · `LangChain` · `ChromaDB` · `Ollama` · `Gradio`

### [GamesLedger](https://github.com/taaha17/games-ledger)
A web app for tracking the games I play: library, ratings, short reviews. Game metadata comes from the IGDB API, accounts are handled by Clerk.
`Next.js` · `TypeScript` · `PostgreSQL` · `Prisma`

### HEXILEXI (lead developer, internal repository)
A vocabulary trainer for primary school children, built into the STREEN reading platform ([live](https://streen-app.ais-lab.de/)). Prompts run in two steps on a local Ollama instance (Gemma 3:12b), and answers are graded on the frontend with Levenshtein distance instead of asking the model again. Tested over four iterations in two primary schools.
`React` · `TypeScript` · `Ollama`

## Tools I use

|  |  |
|---|---|
| **Languages** | Python, TypeScript, Kotlin, Java |
| **AI / LLM** | Ollama, LangChain, ChromaDB, RAG, prompt engineering |
| **Web and data** | React, Next.js, PostgreSQL, MongoDB |
| **Systems** | PySide6/Qt, Docker, Git, Linux, Lab Streaming Layer |

[bytaha.me](https://bytaha.me) · [LinkedIn](https://www.linkedin.com/in/taha-asif17/) · tahasif.1701@gmail.com
