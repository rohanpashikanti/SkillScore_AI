

```
# Skill Score AI

An intelligent, modern web application that analyzes resumes using OCR and Google Gemini API. This project extracts skills, education, and experience from uploaded PDF resumes, then provides AI-generated job recommendations, resume improvement tips, HR-style summaries, and viva questions — all in one elegant interface.

---

## 🚀 Features

- 📝 Upload and analyze PDF resumes
- 🔍 OCR-based resume text extraction (supports scanned images)
- 🤖 AI-powered analysis via Gemini API:
  - Candidate Summary
  - Suggested Job Roles
  - Resume Improvement Tips
  - Viva Questions
  - HR Overview
- 🎨 Beautiful UI with animated stepper and modern neumorphic design
- 🌐 Single-page home with animated blobs and CTA button
- 📄 Secure file upload handling via Flask

---

## 📁 Project Structure

```

project\_resume/
├── app.py                  # Flask backend
├── gemini\_utils.py         # Resume analysis + Gemini API logic
├── templates/
│   ├── home.html           # Animated landing page
│   └── index.html          # Resume upload + analysis view
├── static/
│   ├── style.css           # CSS for both pages
│   └── script.js           # Optional JavaScript
├── uploads/                # Uploaded PDF resumes
├── requirements.txt        # Python dependencies
└── README.md               # Project overview

````

---

## ⚙️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python Flask
- **AI:** Google Gemini API (generative language model)
- **OCR:** Tesseract via `pytesseract` + `pdf2image`

---

## 🛠️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/rohanpashikanti/ai-resume-analyser.git
   cd ai-resume-analyser
````

2. **Create a virtual environment**

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Add your Gemini API Key**

   Open `gemini_utils.py` and set:

   ```python
   GEMINI_API_KEY = "your_actual_api_key"
   ```

5. **Run the app**

   ```bash
   python app.py
   ```

6. **Visit in your browser**

   ```
   http://127.0.0.1:5000/
   ```

---

## 👤 Author

**Rohan Pashikanti**
[Portfolio Website](https://rohanpashikanti.github.io)

---

## 📄 License

This project is open-source and available under the MIT License.

```

---

Let me know if you want me to include badges (e.g. Made with Flask, MIT License), deployment instructions (e.g. Render or Vercel), or create a `requirements.txt` for you.
```
