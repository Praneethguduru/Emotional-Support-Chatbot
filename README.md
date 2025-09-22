# Emotional-Support-Chatbot


**Mental Health Chatbot** is an AI-powered conversational agent designed to provide support, guidance, and resources for mental well-being. It uses **NLP** and pre-trained models to interact empathetically and provide relevant suggestions to users.

## Features

* Conversational AI for mental health support.
* Provides coping strategies and resources.
* Uses pre-trained datasets like **DAIC-WOZ** for emotional and psychological analysis.
* Fast and interactive responses.

## Tech Stack

* **Backend:** Python, Flask
* **Frontend:** React.js
* **ML/NLP Tools:** Transformers, Hugging Face models, NLTK, SpaCy
* **Data:** DAIC-WOZ or other publicly available mental health datasets

## Installation

1. **Clone the repository:**

```bash
git clone <repository_url>
cd Mental-Health-Chatbot
```

2. **Set up Python environment:**

```bash
python -m venv venv
source venv/bin/activate   # Linux/macOS
venv\Scripts\activate      # Windows
pip install -r requirements.txt
```

3. **Set up frontend environment:**

```bash
cd frontend
npm install
npm start
```

## Usage

1. Start the Flask backend:

```bash
python backend/app.py
```

2. Open the frontend in your browser (usually `http://localhost:3000`).
3. Interact with the chatbot for mental health support and guidance.

## Project Structure

```
Mental-Health-Chatbot/
├── backend/
│   └── app.py           # Flask backend
├── frontend/
│   ├── src/components/Chatbot.jsx
│   ├── src/styles/chatbot.css
│   ├── package.json
│   └── index.js
├── datasets/            # Mental health datasets
├── requirements.txt
└── README.md
```

## Future Improvements

* Add voice-based interaction.
* Integrate sentiment and emotion analysis for better responses.
* Provide personalized resource recommendations based on user inputs.

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
