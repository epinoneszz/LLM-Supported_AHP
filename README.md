# LLM-Supported_AHP

This repository contains code and resources for the research article:

**"Human-AI Collaboration in Engineering Design Decisions: Automating AHP Through LLM Analysis of Team Discussions"**

The code demonstrates how Large Language Models (LLMs), specifically OpenAI's GPT and Whisper, can assist in automating the Analytical Hierarchy Process (AHP) based on unstructured team discussions.

## 📘 Overview

This Jupyter Notebook-based workflow performs the following steps:

1. **Transcribes a recorded team discussion** using OpenAI Whisper.
2. **Extracts AHP decision criteria and weights** from the transcription using GPT.
3. **Assigns values to alternatives** based on the criteria and discussion context.
4. **Generates an AHP-based recommendation**.
5. **Creates a final report** in Spanish, formatted in Markdown.

## 📁 Files Included

- `LLM-supported AHP.ipynb` – Main Jupyter Notebook with the complete workflow.
- `transcription.txt` – Case study transcript for selecting a main board for an underwater sensor array.
- `README.md` – This file.

## ⚙️ Requirements

- Python 3.8+
- [openai](https://pypi.org/project/openai/) Python package
- OpenAI API key with access to Whisper and GPT-4o models

Install dependencies via pip:

```bash
pip install openai
```

## 🔐 API Key Setup

To run this notebook, you’ll need an OpenAI API key. It's recommended to set it as an environment variable:

## 🧪 Customization

The notebook is designed to be easily modified:

- Replace `discussion.mp3` with your own audio file.
- Edit the user prompts to tailor the analysis or reporting style.
- Adjust the language of the final report by modifying the prompt.

## 📚 Citation & Acknowledgment

This code supports the following research article (currently under review/publication):

> [Authors TBD]. _Human-AI Collaboration in Engineering Design Decisions: Automating AHP Through LLM Analysis of Team Discussions._ [Journal/Conference TBD].

Please cite this work if you use or adapt this repository in your own research.

## 📄 License

This project is licensed under the MIT License – see [LICENSE](LICENSE) for details.
