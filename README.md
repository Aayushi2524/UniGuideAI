🎓 UniGuide AI

Smart University Document Understanding and Student Assistance System

UniGuide AI is a Generative AI-powered application designed to help university students understand official university notices and documents easily.

Students can upload university notice PDFs and use AI to summarize information, identify important deadlines, create action plans, ask questions and understand notices in multiple languages.

🚀 Features

1. Smart Summary

- Converts lengthy university notices into simple language.
- Presents important information using headings and bullet points.

2. Deadline Detector

- Identifies important dates and deadlines.
- Highlights registration dates, examination dates and events.

3. Student Action Planner

- Creates a checklist of important student tasks.
- Organizes tasks according to priority.

4. Ask Your Notice

- Allows students to ask questions about uploaded documents.
- Generates answers based on the uploaded notice.

5. Language Assistant

- Explains university notices in simple English, Hindi and Kannada.

🛠️ Technologies Used

- Programming Language: Python
- Frontend: Streamlit
- Generative AI: Google Gemini API
- PDF Processing: PyPDF
- Environment Management: Python Dotenv

⚙️ Installation and Setup

Step 1: Clone the repository

git clone https://github.com/Aayushi2524/UniGuideAI.git

Step 2: Open the project folder

cd UniGuideAI

Step 3: Create a virtual environment

python -m venv venv

Step 4: Activate the environment (Windows)

venv\Scripts\activate

Step 5: Install required libraries

python -m pip install streamlit google-genai pypdf python-dotenv

Step 6: Configure Gemini API Key

Create a ".env" file in the project folder and add:

GEMINI_API_KEY=your_api_key_here

Replace "your_api_key_here" with your own Gemini API key.

Important: Never upload your ".env" file or share your API key publicly.

Step 7: Run the application

python -m streamlit run app.py

The application will open in your web browser.

📂 Project Structure

UniGuideAI/
│
├── app.py
├── .gitignore
├── README.md
├── .env
└── venv/

The ".env" and "venv" folders are excluded from GitHub uploads.

🎯 Project Objectives

- Simplify university notices for students.
- Reduce the time required to understand lengthy documents.
- Help students avoid missing important deadlines.
- Provide multilingual document assistance.
- Make university information easier to access and understand.

🔮 Future Enhancements

- Support for more document formats.
- OCR support for scanned PDF documents.
- Student dashboard and notification system.
- Improved document search and retrieval.
- More Indian language support.

👩‍💻 Developer

Project Name: UniGuide AI
GitHub: "Aayushi2524" (https://github.com/Aayushi2524)

---

UniGuide AI – Making University Information Simple, Smart and Accessible.
