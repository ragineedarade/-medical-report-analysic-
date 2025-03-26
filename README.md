 
 
# 🏥 Medical Report Analysis App (Streamlit + Gemini API)  

A **Streamlit-based web application** that analyzes medical reports using **Google Gemini Pro API**. This app supports **image uploads** and provides AI-generated medical insights in **Hindi or English**.  

## 🚀 Features  
✅ Upload medical reports **(PDF, TXT, or Images - JPG, PNG)**  
✅ Extract text from images using **OCR**  
✅ AI-powered medical insights using **Gemini Pro**  
✅ Multilingual support: **English & Hindi**  
✅ Data visualization (Charts, Graphs)  

## 🛠️ Installation  

### 1️⃣ **Clone the Repository**  
```bash
git clone https://github.com/your-username/medical-report-analysis.git
cd medical-report-analysis
2️⃣ Install Required Packages
bash
 
pip install -r requirements.txt
3️⃣ Set Up Google Gemini API
Get your API key from Google AI Studio.

Add your API key to an .env file:

plaintext
 
GEMINI_API_KEY=your_api_key_here
4️⃣ Run the Streamlit App
bash
 
streamlit run app.py
📁 File Structure
bash
 
medical-report-analysis/
│── app.py              # Main Streamlit app
│── requirements.txt    # Dependencies
│── README.md           # Documentation
│── .env                # API Key (Ignored in Git)
│── data/               # Sample medical reports
│── models/             # AI/ML models (if applicable)
│── assets/             # Images and other assets
🏥 How to Use?
1️⃣ Upload a medical report (PDF, TXT, or Image format)
2️⃣ The app extracts text from the image (if applicable)
3️⃣ AI generates insights using Gemini Pro
4️⃣ Choose language: English or Hindi
5️⃣ View medical analysis and download the report

🔑 Dependencies
Python 3.8+

Streamlit

Google Generative AI (Gemini Pro API)

Pandas, OpenCV, Matplotlib

Tesseract OCR (for image text extraction)

To install Tesseract on Ubuntu:

bash
Copy
Edit
sudo apt install tesseract-ocr
On Windows, download from: Tesseract OCR

📌 Example Output
Report	AI Summary (English)	AI Summary (Hindi)
Blood Test	Low hemoglobin detected	हीमोग्लोबिन का स्तर कम है
X-Ray	No fracture found	कोई फ्रैक्चर नहीं पाया गया
🤝 Contributing
Pull requests are welcome!

📜 License
MIT License

Would you like to add database storage or voice-based AI analysis? 🚀😊

yaml
 
---

### ✨ **This README Covers:**  
✔️ Streamlit + Gemini API setup  
✔️ Image upload and OCR text extraction  
✔️ AI-generated insights in **Hindi & English**  

Let me know if you need any modifications! 🚀🔥
