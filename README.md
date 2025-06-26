# MediGo
Website integrated with Python ML models
MediGo is an innovative AI-powered pharmacy web application designed to simplify the medicine ordering process. It leverages OCR (Optical Character Recognition) to read handwritten prescriptions and a deep learning model to detect pneumonia from chest X-ray images. The project combines modern web development with machine learning to assist both patients and pharmacists efficiently.

🚀 Features
📝 OCR Integration: Upload a prescription (handwritten or printed), and the app automatically extracts medicine names.

🧠 Pneumonia Detection: Upload a chest X-ray image, and the AI model predicts whether the patient has pneumonia or not.

🌐 Responsive Frontend: Clean, user-friendly interface built using HTML, CSS, and JavaScript.

🤖 TensorFlow/Keras Backend: AI model trained for medical image classification and integrated via a Flask server.

🛒 Smart Ordering System: Detected medicines are auto-added to the cart for faster checkout.

🏗 Tech Stack
Layer	Technologies
Frontend	HTML, CSS, JavaScript
Backend	Python (Flask)
AI/ML	TensorFlow / Keras, OpenCV, NumPy
OCR	Tesseract OCR
Deployment	Localhost / XAMPP (for demonstration)

📂 Project Structure
cpp
Copy
Edit
Medigo/
├── static/
│   └── styles.css
├── templates/
│   └── index.html
├── model/
│   └── pneumonia_model.h5
├── uploads/
│   └── (uploaded images & prescriptions)
├── app.py
├── ocr_utils.py
├── pneumonia_predict.py
└── README.md
🧠 How the AI Works
Pneumonia Detection:

Dataset: Chest X-ray images (Kaggle dataset)

Model: Convolutional Neural Network (CNN)

Output: "Pneumonia" or "Normal"

OCR:

Tool: Tesseract OCR

Use: Extracts medicine names from uploaded images of prescriptions

⚙ How to Run Locally
Clone the repository:

bash
Copy
Edit
git clone https://github.com/mohitvenom/Medigo.git
cd Medigo
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Flask app:

bash
Copy
Edit
python app.py
Visit in browser:

Arduino
Copy
Edit
http://localhost:5000/
🧪 Sample Use Cases
📷 Upload a chest X-ray to get pneumonia prediction.

🧾 Upload a doctor’s prescription image to auto-detect medicines.

🛍 Confirm and place the order from the detected list.
