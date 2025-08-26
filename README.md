Personality Prediction Through CV

This project predicts a candidate’s personality traits by analyzing resume details and self-entered psychological factors.
It uses Python, scikit-learn, NLTK, spaCy, and Tkinter for GUI.

🚀 Features

Extracts key details from resumes (name, skills, education, certifications, etc.) using PyResparser.

Takes additional psychological factors input (Openness, Conscientiousness, Extraversion, Agreeableness, Neuroticism).

Predicts personality using a Logistic Regression model trained on a dataset.

User-friendly Tkinter GUI for uploading resumes and entering personal details.

🛠️ Installation
1. Clone the repository
git clone https://github.com/yourusername/Personality-Prediction-Through-CV.git
cd Personality-Prediction-Through-CV

2. Create virtual environment (recommended)
py -m venv .venv
.\.venv\Scripts\activate

3. Install dependencies
pip install -r requirements.txt


If requirements.txt is missing, install manually:

pip install scikit-learn pandas numpy nltk spacy pyresparser

4. Download NLTK data
import nltk
nltk.download('stopwords')
nltk.download('punkt')
nltk.download('wordnet')
nltk.download('averaged_perceptron_tagger')
nltk.download('maxent_ne_chunker')
nltk.download('words')

5. Download spaCy model
py -m spacy download en_core_web_sm

▶️ Usage

Run the application:

py main.py


Steps:

Enter your name, age, gender, and psychological ratings.

Upload your resume (PDF/DOCX).

Click Submit to see the predicted personality and parsed resume data.

📂 Project Structure
.
├── main.py                # Main GUI and ML logic
├── training_dataset.csv   # Training data for personality prediction
├── requirements.txt       # Dependencies
└── README.md              # Documentation

⚠️ Common Issues

NLTK stopwords not found → Run nltk.download('stopwords')

spaCy model errors → Run py -m spacy download en_core_web_sm

pyresparser config error → Edit resume_parser.py to use "en_core_web_sm" instead of local path

Matcher.add() error → Update utils.py (matcher.add('NAME', pattern))

👨‍💻 Author

Kaleel Ahamed M A
📧 Email: kaleelahamed36@gmail.com

📱 Phone: 8903627781
🔗 LinkedIn

💻 GitHub
