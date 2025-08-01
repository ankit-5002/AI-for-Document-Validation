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

AI_Document_Validation/<br>
│── app.py # Main Flask application<br>
│── requirements.txt # Dependencies<br>
│── static/ # CSS, JS, Images<br>
│── templates/ # HTML templates<br>
│── uploads/ # Uploaded documents<br>
│── validators/ # Validation functions<br>
└── README.md # Project documentation<br>


---

## ⚙️ Installation  

1️⃣ Clone the repository  
- git clone https://github.com/ankit_5002/AI-for-Document-Validation.git<br>
- cd AI-for-Document-Validation

2️⃣ Create a virtual environment and activate it
- python -m venv venv
- source venv/bin/activate   # For Linux/Mac
- venv\Scripts\activate      # For Windows

3️⃣ Install dependencies
- pip install -r requirements.txt

4️⃣ Run the Flask server
- python app.py

5️⃣ Open in browser
- http://127.0.0.1:5000


## 🚧 Future Enhancements<br>
🔹 Support for more document types (Passport, Driving License)<br>
🔹 Advanced AI-based field detection<br>
🔹 Multi-language OCR support<br>
🔹 REST API for external integrations<br>

## 🤝 Contributing<br>
Contributions are welcome! Please fork this repo and submit a pull request.<br>

## 📜 License
This project is licensed under the MIT License – feel free to use and modify it.
---

Do you also want me to add **GitHub badges (Python version, Flask, MIT License)** at the top to make it look more professional?

