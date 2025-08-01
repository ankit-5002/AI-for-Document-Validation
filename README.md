# 🧠 AI Document Validation using Python Flask  

An **AI-powered document validation system** built with **Python Flask**.  
This application allows users to upload **images or PDFs of identity documents** (Aadhaar & PAN cards), automatically extracts the content using **OCR (EasyOCR)**, detects the document type, validates key fields (ID number, DOB, etc.), and generates a **detailed validation report**.  

---

## 🚀 Features  

- ✅ Upload image or PDF files  
- ✅ OCR-based text extraction with **EasyOCR**  
- ✅ Detects and validates **Aadhaar** and **PAN cards**  
- ✅ Field validations:  
   - Aadhaar number (12-digit format)  
   - PAN number (10-character format)  
   - Date of Birth (DOB)  
   - Gender  
   - Father's Name  
- ✅ Displays detected document type and a **validation score**  
- ✅ Clean and responsive **HTML/CSS frontend**  

---

## 🛠️ Tech Stack  

- **Backend:** Python Flask  
- **OCR:** EasyOCR  
- **Frontend:** HTML, CSS, Bootstrap  
- **Validation:** Regex-based checks  
- **Deployment:** Flask server  

---

## 📂 Project Structure  

AI_Document_Validation/
│── app.py # Main Flask application
│── requirements.txt # Dependencies
│── static/ # CSS, JS, Images
│── templates/ # HTML templates
│── uploads/ # Uploaded documents
│── validators/ # Validation functions
└── README.md # Project documentation

