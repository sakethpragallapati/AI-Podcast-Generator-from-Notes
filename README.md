# AI Podcast Generator from Notes

**AI Podcast Generator from Notes** is a Google Colab–based project that transforms written study material such as notes or PDF content into conversational podcast scripts using **Large Language Models (LLMs)** and **Text-to-Speech (TTS)** systems.

---

## Overview
This project enables users to automatically convert their lecture notes or topic summaries into a well-structured podcast-style conversation. It generates:
- A concise summary of the uploaded material.
- A natural, two-host podcast dialogue between *Alex* and *Jordan*.
- Optional speech output using a TTS engine such as ElevenLabs or gTTS.

This tool is designed for students, educators, and creators who want to repurpose educational content into engaging audio discussions.

---

## Features
- Extracts and processes text from uploaded PDF or note files.
- Generates accurate summaries using transformer-based models (e.g., T5, LongT5).
- Produces conversational scripts between two hosts.
- Optionally converts text into audio output using TTS.
- Fully runnable in Google Colab.

---

## File Structure
```
AI-Podcast-Generator-from-Notes/
│
├── PODCAST_generator.ipynb   # Main Colab notebook
├── README.md                  # Project description (this file)
└── sample_data/               # Optional folder for input PDFs or notes
```

---

## Setup and Usage
1. Open the notebook directly in Google Colab:  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/11H8Gkx41-Mw0tGQOaBO79GIKk_qvLMkU)

2. Upload your notes or PDF file using the Colab file upload interface.

3. Run all cells to:
   - Summarize the content.
   - Generate a structured podcast dialogue.
   - (Optionally) convert the script into audio.

4. Download the generated script or audio file for use in podcasts or educational platforms.

---

## Technology Stack
- **Python 3**
- **Google Colab**
- **Hugging Face Transformers (T5 / LongT5)**
- **PyPDF2** for PDF text extraction
- **ElevenLabs API** or **gTTS** for speech generation

---

## Example Output
**Input:** Case-based reasoning lecture notes  
**Output:** A 4-minute podcast conversation between Alex and Jordan discussing the concept interactively and informatively.

---

## Author
**Saketh Pragallapati**  
[LinkedIn](https://linkedin.com/in/sakethpragallapati](https://www.linkedin.com/in/pragallapati-saketh-143384290/))  
[GitHub](https://github.com/sakethpragallapati)
