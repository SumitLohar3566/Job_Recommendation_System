💼 CareerConnect Pro

CareerConnect Pro is a smart resume-based job recommendation web application built using Python and Streamlit.
It analyzes your resume, extracts relevant skills, and finds real-time job opportunities from multiple job platforms.

🚀 Features

📄 PDF Resume Upload

🧠 Automatic Skill Extraction

🌐 Live Job Fetching from APIs

Adzuna

Remotive

Jooble

⚡ Parallel API Calls for Faster Results

🎨 Modern UI with Custom Job Cards

📱 Mobile-Responsive Design

🛠 Tech Stack

Frontend & Backend: Streamlit

Language: Python

APIs: Adzuna, Remotive, Jooble

PDF Parsing: pdfplumber

📂 Project Structure
CareerConnect-Pro/
│
├── app.py                # Main Streamlit application
├── requirements.txt      # Project dependencies
├── README.md             # Project documentation
├── screenshots/          # App screenshots (optional)
│   ├── home.png
│   ├── skills.png
│   └── jobs.png

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/CareerConnect-Pro.git
cd CareerConnect-Pro

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Application
streamlit run app.py

▶️ How It Works

Upload your resume in PDF format

The app extracts skills using keyword matching

Jobs are fetched from multiple APIs simultaneously

Relevant jobs are displayed as interactive cards

Click Apply Now to visit the job source

📸 Screenshots
<img width="1912" height="788" alt="Screenshot 2026-01-15 065511" src="https://github.com/user-attachments/assets/e206e53a-4e83-4382-9cb1-3c085ced828d" />
<img width="1812" height="597" alt="Screenshot 2026-01-15 065548" src="https://github.com/user-attachments/assets/2c518b87-5ee6-4301-b718-ed15194d0f6e" />
<img width="1742" height="627" alt="Screenshot 2026-01-15 065601" src="https://github.com/user-attachments/assets/56e1e805-ec2e-4c58-a7a2-8637dec98747" />
<img width="1561" height="765" alt="Screenshot 2026-01-15 065616" src="https://github.com/user-attachments/assets/59a4d2d3-5a4a-4e98-8d92-24f426161112" />
<img width="1698" height="644" alt="Screenshot 2026-01-23 143741" src="https://github.com/user-attachments/assets/a9e77161-9961-4484-bc54-a86a654ccd44" />
<img width="1914" height="855" alt="Screenshot 2026-01-23 143754" src="https://github.com/user-attachments/assets/a2da6af3-fbe3-4c71-86f9-b5dfc3ce9d56" />

🔐 API Configuration

Update API keys inside app.py:

API_KEYS = {
    "ADZUNA_ID": "your_id",
    "ADZUNA_KEY": "your_key",
    "JOOBLE_KEY": "your_key",
    "REMOTIVE_KEY": None
}


⚠️ Do not expose real keys in public repositories

🌱 Future Enhancements

🔍 Advanced NLP-based skill extraction

🤖 AI job matching score

🧾 Resume improvement suggestions

🌍 Location & experience filters

☁️ Deployment on Streamlit Cloud

📞 Contact Developer: Sumit Lohar 📧 Email:sumitlohar063@gmail.com 🐙 GitHub: https://github.com/SumitLohar3566🔗 LinkedIn:(https://www.linkedin.com/in/sumit-lohar-498341317/)


