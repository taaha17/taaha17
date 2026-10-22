# Taha Asif

Student Research Engineer at the [Centre for Assistive Technology Rhine-Ruhr (ZAT)](https://zat.nrw/) · B.Sc. Infotronic Systems Engineering at [Rhine-Waal University of Applied Sciences](https://www.hochschule-rhein-waal.de/)

I build assistive software and local LLM pipelines—eye-tracking and BLE sensor streams, closed-loop adaptive interfaces in Python/Qt, document parsers, and on-device retrieval systems that keep user data on the machine.

[**bytaha.me**](https://bytaha.me) · [**CV (EN)**](https://bytaha.me/Taha_Asif_CV_EN.pdf) · [**CV (DE)**](https://bytaha.me/Taha_Asif_Lebenslauf.pdf) · [**LinkedIn**](https://www.linkedin.com/in/taha-asif17/) · [tahasif.1701@gmail.com](mailto:tahasif.1701@gmail.com)

---

## Publication

**[ADHD by Design: Expert Co-Design and Prototype Development Towards a Pro-Adaptive Reading Support System](https://doi.org/10.18420/muc2026-mci-ws107-312)**  
H. Ashfaque, **T. Asif**, A. F. Krause, N. Wild-Wall, C. Ressel, K. Kannen · *Mensch und Computer 2026 (GI Digital Library)* · [`doi:10.18420/muc2026-mci-ws107-312`](https://doi.org/10.18420/muc2026-mci-ws107-312)

## Selected Work

### ADHD Pro-Adaptive Reading Assistant · *ZAT Rhine-Ruhr* ([2-min demo](https://bytaha.me/adhd-demo.mp4) · [paper](https://doi.org/10.18420/muc2026-mci-ws107-312))
A desktop reading environment in PySide6/Qt that adapts visual support in real time. I implemented the closed-loop control layer (Section 3.2 of the paper): a 60 s rolling reading-velocity estimator and a pharmacodynamic medication-decay model feed the Dynamic Support Index ($\text{DSI} \in [0,1]$), smoothed with an EMA ($\alpha = 0.1$) and $\pm 3\%$ dead-band hysteresis across five visual tiers (plain text, bionic font, line highlight, word highlight, peripheral blur). Evaluated with UX/UI professionals with ADHD ($N=5$, mean SUS **88.50**).  
`Python` · `PySide6/Qt` · `Tobii Eye-Tracking` · `Lab Streaming Layer` · `Docling` · `PyMuPDF4LLM`

### HexiLexi — AI Vocabulary Companion · *Lead Developer* ([live on STREEN](https://streen-app.ais-lab.de/) · [report PDF](https://bytaha.me/hexilexi-paper.pdf) · [poster PDF](https://bytaha.me/hexilexi-poster.pdf))
An inquiry-based vocabulary trainer for 8-to-10-year-olds embedded in the STREEN reading platform for LeseLab. Uses a two-step *Architect → Builder* prompt pipeline on a local Ollama instance (Gemma 3:12b), grades typed and German Web Speech answers in the browser via Levenshtein similarity, and queues concurrent requests with UI state-locking. Tested across four classroom iterations in two primary schools ($N=38$).  
`React` · `TypeScript` · `Ollama (Gemma 3:12b)` · `Ant Design`

### [Movella DOT → LSL Pipeline](https://github.com/taaha17/movella-dot-lsl-pipeline) · *Open-Source Maintainer*
Streams 16 channels per sensor at 30 Hz (quaternions, Euler angles, accelerometer, gyroscope, magnetometer) from Movella Xsens DOT IMUs over BLE into Lab Streaming Layer, with terminal and 3D orientation viewers for Ubuntu and Windows.  
`Python` · `BLE` · `Lab Streaming Layer` · `uv`

### [HSRW RAG Chatbot "Zero"](https://github.com/taaha17/hsrw-rag-chatbot)
Local-first academic advisor over 500+ pages of university regulations. Combines query intent routing with hybrid BM25 + ChromaDB vector search on Ollama (Llama 3.2).  
`Python` · `LangChain` · `ChromaDB` · `Ollama` · `Gradio`

### [GamesLedger](https://github.com/taaha17/games-ledger)
Full-stack application for cataloguing games, ratings, and reviews with IGDB metadata and Clerk authentication.  
`Next.js` · `TypeScript` · `PostgreSQL` · `Prisma`

## Stack

| Area | Tools |
|---|---|
| **Languages** | Python, TypeScript, Kotlin, Java |
| **AI & Retrieval** | Ollama, LangChain, ChromaDB, Docling, PyMuPDF4LLM, RAG |
| **Desktop & Sensors** | PySide6/Qt, Pygame, Tobii Eye-Tracking, Lab Streaming Layer (LSL), BLE |
| **Web & Data** | React, Next.js, PostgreSQL, MongoDB, Prisma, Docker, Linux, Git |
