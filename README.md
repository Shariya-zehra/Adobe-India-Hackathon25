🏁 Adobe India Hackathon 2025 – Round 1 Submissions
This repository contains submissions for Round 1 of the Adobe India Hackathon 2025, including:

📘 Challenge 1A – PDF Structure Extraction (Offline, Python, CLI)

🌐 Challenge 1B – PDF Outline Viewer Web App (Flask + HTML/CSS/JS)

📁 Challenge 1A – PDF Structure Extractor (Offline CLI Tool)
A command-line tool that uses Python + PyMuPDF to extract a structured outline from PDF files based on font sizes. It classifies content into headings such as H1, H2, H3, and saves the result in JSON format.

🔧 Features:
Categorizes headings using font size hierarchy.

Outputs results into cleanly formatted .json files.

Works offline – no internet or UI required.

Easy to use with an input/ and output/ folder structure.

🖥️ Folder Structure:
Challenge_1b/
├── backend/
│   ├── app.py
│   ├── extract_outline.py
│   └── requirements.txt
├── frontend/
│   ├── index.html
│   ├── script.js
│   ├── style.css
├── input/
├── output/

🌐 Challenge 1B – PDF Outline Viewer Web App
An interactive web app built using Flask (Python backend) and HTML/CSS/JS (frontend). Users can upload PDF files, and the app displays a structured heading outline in a collapsible JSON viewer with the ability to download the output.

✨ Features:
Upload any PDF and extract headings in real-time.

View structured output in a tree-style collapsible format.

💾 Download button for saving JSON results.

⏳ Loader/spinner during upload process.

Fully styled UI with dark-themed responsive layout.

Works on localhost using Flask backend and simple HTTP server for frontend.

🖥️ Folder Structure:
Challenge_1b/
├── backend/
│   ├── app.py
│   ├── extract_outline.py
│   └── requirements.txt
├── frontend/
│   ├── index.html
│   ├── script.js
│   ├── style.css
├── input/
├── output/


✅ Tools & Tech Used
Python

PyMuPDF (fitz)

Flask

HTML, CSS, JavaScript

Git + GitHub

PowerShell (for file operations)

JSON formatting

👤 Authors
🧑‍💻 Siddharth Mishra (Challenge 1A & 1B implementation, UI, logic)

👩‍💻 [Collaborator GitHub link or names if applicable]
