
# VetAI - Veterinary AI Chatbot

![VetAI Logo](https://github.com/Promasterr/VetAI/blob/main/logo.png) *(Replace with actual logo if available)*

## 📌 Overview
VetAI is an AI-powered veterinary chatbot designed to assist in diagnosing animal diseases and answering pet-related queries. The chatbot leverages **Llama 3 ALOE Beta** developed by **HPAI-BSC** for conversational responses. LLama 3 ALOE is a fine-tuned version of LLama 3 8B on medical dataset. 

## 🏗 Project Structure
```
VetAI/
│── frontend/    # Flutter app for user interaction
│── backend/     # Python-based AI model and API
│── README.md    # Project documentation
│── .gitignore   # Files to be ignored by Git
```

## 🚀 Features
- **Conversational AI**: Uses Llama 3 to provide natural, interactive responses.
- **Medical Diagnosis**: Assists in identifying animal diseases based on symptoms.
- **Follow-up Questions**: Dynamically asks relevant questions to refine diagnosis.
- **Flutter Frontend**: Intuitive user interface for seamless interaction.
- **Python Backend**: AI processing and API for chatbot responses.

## 🛠 Tech Stack
### Frontend (Flutter)
- Flutter 3.16.0
- Firebase Authentication
- Cloud Firestore
- Provider (State Management)

### Backend (Python)
- Flask/FastAPI (for API)
- Hugging Face Transformers (Llama 3, BERT)
- PyTorch

## ⚡ Installation
### Clone Repository
```bash
git clone https://github.com/your-username/VetAI.git
cd VetAI
```

### Frontend Setup
```bash
cd frontend
flutter pub get
flutter run
```

### Backend Setup
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python app.py  # Start API server
```

## 📡 API Endpoints
| Endpoint        | Method | Description |
|---------------|--------|-------------|
| `/getresponse`| POST   | Generates response based on the prompt |
| `/settitle`   | POST   | Generates the title of conversation    |
| `/stt`        | POST   | Converts speech to text                |
| `/endpu`      | POST   | Updates the endpoint of models         |

## 📌 Usage
- Open the Flutter app and sign in.
- Ask VetAI about your pet’s symptoms.
- VetAI will ask follow-up questions for better diagnosis.
- The chatbot provides a probable diagnosis with treatment suggestions.

## 📝 Future Enhancements
- 🏥 FineTuning a single model instead of using two models
- 📊 Image diagnosis
- 📱 Mobile app deployment on Play Store & App Store.

## 🤝 Contributing
1. Fork the repository
2. Create a new branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Added feature X'`)
4. Push to the branch (`git push origin feature-name`)
5. Open a Pull Request


## 📧 Contact
- **Developer:** Muhammad Abdul Ali Khan
- **Email:** promaster1436@gmail.com
- **GitHub:** [Promasterr](https://github.com/Promasterr)

---
Feel free to modify this README to suit your project’s needs! 🚀
