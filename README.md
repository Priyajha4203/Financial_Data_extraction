# Financial_Data_extraction

📌 Project Overview
This project automates the extraction of financial details from PDF reports using a combination of Large Language Models (LLMs), NLP (SpaCy), and Regex. The extracted data includes:
✅ Company Name
✅ Report Date
✅ Profit Before Tax
✅ Revenue
✅ Net Profit After Tax

The extracted information is structured and saved in JSON format, making it easy to analyze and integrate with financial systems.

🚀 Features
🔹 Extracts financial data from PDFs 📄
🔹 Uses OpenAI’s GPT-4 for high accuracy 🤖
🔹 Falls back to Regex & SpaCy for reliability 🔍
🔹 Saves extracted data in structured JSON format 📊
🔹 Automates processing for multiple PDFs 📂

🛠️ Tech Stack
Python 🐍
OpenAI GPT-4 (for financial entity extraction)
PyMuPDF (fitz) (for PDF text extraction)
SpaCy (for Named Entity Recognition)
Regex (for structured data extraction)
JSON (for storing extracted data)

⚡ How It Works
1️⃣ Extracts text from PDFs using PyMuPDF
2️⃣ Processes the text with GPT-4 to extract financial details
3️⃣ Uses Regex & SpaCy as a fallback method
4️⃣ Saves the structured data in JSON format

