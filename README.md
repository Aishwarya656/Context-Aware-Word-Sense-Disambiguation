# Context-Aware Word Sense Disambiguation Using NLP and WordNet

An NLP-based web application that identifies the appropriate meaning of an ambiguous word by analyzing its surrounding context.

## Overview

Words can have multiple meanings depending on how they are used in a sentence. This project aims to identify the most appropriate meaning of a target word using Natural Language Processing (NLP) and WordNet.

The application provides a simple web interface built with Flask, allowing users to enter a sentence and explore the meaning of an ambiguous word in context.

## Features

- **Context-aware analysis:** Uses sentence context to help determine the intended meaning of a word.
- **WordNet integration:** Uses WordNet as a lexical resource for word meanings and synsets.
- **NLP processing:** Uses NLTK for natural language processing.
- **Web interface:** Provides a user-friendly interface through Flask.
- **Sense identification:** Helps distinguish between different meanings of ambiguous words.

## Technologies Used

- **Programming Language:** Python
- **NLP Library:** NLTK
- **Lexical Database:** WordNet
- **Web Framework:** Flask
- **Frontend:** HTML and CSS

## Project Structure

```text
Word_Sense_Disambiguation_Enhanced/
├── app.py
├── wsd.py
├── requirements.txt
├── README.md
├── reports/
│   └── analysis_report_template.md
├── static/
│   └── style.css
└── templates/
    └── index.html
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Aishwarya656/Context-Aware-Word-Sense-Disambiguation.git
cd Context-Aware-Word-Sense-Disambiguation
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python app.py
```

Open the local URL displayed in your terminal, typically `http://127.0.0.1:5000/`.

## How It Works

1. The user enters a sentence containing an ambiguous word.
2. The application processes the input using Python and NLTK.
3. WordNet provides lexical information about possible meanings.
4. The system uses the surrounding context to help identify the intended word sense.
5. The result is presented through the Flask web interface.

## Project Status

**Ongoing Development**

Further improvements may include enhanced word-sense selection, additional evaluation examples, and improved handling of different sentence contexts.

## Future Enhancements

- Improve disambiguation accuracy.
- Support more ambiguous words and contextual examples.
- Add a test dataset and evaluation metrics.
- Improve the user interface and result explanations.

## Author

**Aishwarya**

GitHub: https://github.com/Aishwarya656

## License

This project is available for educational and learning purposes.
