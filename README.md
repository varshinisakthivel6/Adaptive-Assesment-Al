
# code_buddies

# Adaptive Assessment System

This is an AI-powered adaptive assessment system that provides personalized tests, immediate feedback, a chatbot tutor, and file uploads for assignments.

## Features

- **Adaptive Testing:** Adjusts difficulty based on performance.
- **Immediate Feedback:** Shows correct and incorrect answers instantly.
- **Chatbot Tutor:** AI-powered assistant for learning support.
- **File Uploads:** Allows students to upload assignments.
- **Smooth UI/UX:** Modern, engaging, and responsive design.

---

## Installation Guide

### 1. Clone the Repository

```bash
git clone https://github.com/varshinisakthivel6/code_buddies.git
cd code_buddies
```

### 2. Set Up Python Virtual Environment

Create a virtual environment:

```bash
python -m venv venv
```

**For Windows:**

```bash
venv\Scripts\activate
```

**For macOS/Linux:**

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Project Structure

```text
code_buddies/
├── pages/
│   ├── chatbot.py
│   └── uploads.py
├── main.py
├── requirements.txt
└── README.md
```

- `main.py` – Entry point for the assessment system.
- `pages/chatbot.py` – AI chatbot functionality.
- `pages/uploads.py` – File upload functionality.
- `requirements.txt` – List of project dependencies.
- `README.md` – Project documentation.

---

## Running the Application

Run the following command in your terminal:

```bash
streamlit run main.py
```

This will launch the assessment system in your web browser.

---

## Usage

1. **Start the Assessment:** Click "Start Test" and answer the multiple-choice questions.
2. **Receive Instant Feedback:** View correct and incorrect responses.
3. **Chat with AI Tutor:** Navigate to the chatbot page for assistance.
4. **Upload Assignments:** Use the Uploads page to submit assignments.
5. **View Performance Reports:** Review your assessment results.

---

## License

This project is available under the MIT License, provided the repository includes the applicable MIT license.

---

## Contributions

Contributions are welcome! Feel free to fork the repository, create issues, or submit pull requests.

---

## Contact

For questions or suggestions, please open an issue in this GitHub repository.
