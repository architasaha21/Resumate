# 🧠 **Resumate**

**Resumate** is a smart resume analyzer built using **Flask**, **Natural Language Processing (NLP)**, and **Machine Learning**. It extracts key information from resumes and classifies them using trained models — perfect for quick candidate screening or building custom HR tools.



## 🚀 **Features**

-  Upload and analyze resumes (PDF)
-  Extract and vectorize key terms using `TfidfVectorizer`
-  Predict the domain/skillset based on resume content
-  Powered by trained ML models (Decision Tree, Random Forest)
-  Clean Flask-based web interface



## 🛠️ **Tech Stack**

- **Backend**: Python, Flask
- **ML/NLP**: scikit-learn, TfidfVectorizer, DecisionTreeClassifier, RandomForestClassifier
- **PDF Parsing**: PyPDF2
- **Frontend**: HTML, Jinja2



## ⚙️ **Getting Started (Local Setup)**

```bash
# 1. Clone the repo
git clone https://github.com/your-username/resumate.git
cd resumate

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the Flask app
python app.py

# 4. Open in browser
http://localhost:5000
