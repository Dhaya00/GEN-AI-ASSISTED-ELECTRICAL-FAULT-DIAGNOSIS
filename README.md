⚡ Gen-AI Based Electrical Fault Diagnosis Chatbot

An intelligent AI-powered chatbot that diagnoses electrical faults using real-world sensor and power system data.
This project combines Generative AI (Google Gemini) with vector similarity search to provide accurate and explainable fault analysis.

🚀 Project Overview

Electrical systems generate large volumes of sensor and electrical parameter data. Identifying faults manually is time-consuming and requires expert knowledge.

This project solves that problem by building a Retrieval-Augmented Generation (RAG) based chatbot that:

✔ Understands user-described electrical symptoms

✔ Searches similar historical fault cases from datasets

✔ Uses Google Gemini AI to generate expert-level diagnosis

✔ Provides causes, explanations, and preventive measures


🧠 Technologies Used
Technology	                        Purpose
Python	                            Core programming
Streamlit                          	Web app interface
Google Gemini API                  	Generative AI diagnosis
LangChain                          	AI pipeline framework
HuggingFace Embeddings	            Text-to-vector conversion
Chroma DB	                        Vector database for similarity search
Pandas	                            Dataset processing

📂 Datasets Used

1. Fault Dataset
Contains grid currents, rotor currents, voltages, power values, and labeled fault types.

⚙️ How the System Works

1️⃣ User enters fault symptoms (example: “High stator current in phase B and low voltage”)

2️⃣ System converts datasets into vector embeddings

3️⃣ Chroma DB finds the most similar historical fault cases

4️⃣ Gemini AI analyzes retrieved data

5️⃣ Chatbot returns:
    1.Fault Type
    2.Technical Cause
    3.Electrical Explanation
    4.Preventive Measures

APPLICATION LINK
https://dhaya00-gen-ai-assisted-electrical-fault-diagno-dhaya-py-48pbpk.streamlit.app/
