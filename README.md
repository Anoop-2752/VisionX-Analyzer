# VisionX-Analyzer

![Image](https://github.com/user-attachments/assets/33c72b65-10c7-4f8d-a183-853a5935f851)



## 🚀Project Overview
VisionX Analyzer is an AI-powered **multimodal image analysis** system that allows users to **upload images and ask questions** about them. The application processes the images using advanced **machine learning models (LLaMA & LLaVA)** and provides **detailed textual explanations**.

## 🎯 Features
- ✅ Upload an image and receive AI-generated insights  
- ✅ Ask questions about the image for **detailed analysis**  
- ✅ Uses **LLaMA-3.2-11B & LLaVA-3.2-90B models** for responses  
- ✅ **FastAPI-based backend** for handling image uploads & API requests  
- ✅ Interactive **front-end with Tailwind CSS**  

## 🏗️ Project Structure
```
VisionX-Analyzer/
│── templates/              # HTML Templates (index.html)
│── static/                 # Static assets (CSS, JS)
│── main.py                 # Core image processing logic
│── app.py                  # FastAPI server implementation
│── .env                    # Environment variables (API Keys)
│── requirements.txt        # Project dependencies
│── README.md               # Documentation
```

## ⚡ Technologies Used
- **FastAPI** (Backend API)
- **Python & PIL** (Image Processing)
- **OpenAI's GPT Models** (LLaMA-3.2, LLaVA-3.2)
- **Tailwind CSS** (Frontend Styling)
- **Jinja2 Templates** (Dynamic UI)

## 🔧 Installation & Setup
### 1️⃣ Clone the repository
```sh
git clone https://github.com/your-username/VisionX-Analyzer.git
cd VisionX-Analyzer
```

### 2️⃣ Install dependencies
```sh
pip install -r requirements.txt
```

### 3️⃣ Set up API Keys
Create a `.env` file and add your **Groq API Key**:
```env
GROQ_API_KEY=your_api_key_here
```

### 4️⃣ Run the application
```sh
uvicorn app:app --reload
```

## 🎮 Usage
1️⃣ Open the app in your browser: `http://127.0.0.1:8000/`
2️⃣ Upload an image
3️⃣ Enter a question about the image
4️⃣ Click **Submit** and get AI-generated insights

## 📌 Future Enhancements
- 🔹 Support for **more AI models** (BLIP-2, DALL·E)
- 🔹 Integrate **speech-to-text** for voice-based queries
- 🔹 **Mobile app version** for real-time analysis

## 🤝 Contribution
Contributions are welcome! Fork the repo, create a branch, and submit a PR.

## 📜 License
This project is licensed under **MIT License**.

---
**Made with ❤️ for AI-Powered Image Understanding**


