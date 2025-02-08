# 🌦️ WarmlyV2 - AI Weather Chatbot  

**WarmlyV2** is a conversational weather chatbot built with **Streamlit, OpenAI, and DataForSEO**.  
It provides **weather updates** and engages users with AI-generated responses in different tones.

---
## 🚧 Work in Progress
This project is **experimental** and still under active development.  
- Some features may not work as expected.  
- Improvements and bug fixes are in progress.  
- Future updates will enhance AI responses and user interaction.

## 🚀 Features
- 🌍 **Fetches real-time weather data** using **OpenWeatherMap API**.
- 🧠 **AI-generated responses** using OpenAI.
- 🎭 **Custom behavior traits** (Funny, Charismatic, etc.).
- 🜣️ **Supports multiple languages** (English, Swahili, French).
- 🛠️ **Built with** Python, Streamlit, and LangChain.

---

## 🛠️ Installation & Setup
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/rahul-vinay/warmlyv2.git
cd warmlyv2
```

### **2️⃣ Create a Virtual Environment**
```bash
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows
```

### **3️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **4️⃣ Set Up Environment Variables**
Create a `.env` file inside the `warmlyv2` directory:
```bash
touch .env
```
Add your API keys inside `.env`:
```
OPENWEATHERMAP_API_KEY=your_openweathermap_api_key
OPENAI_API_KEY=your_openai_api_key
DATAFORSEO_LOGIN=your_dataforseo_login
DATAFORSEO_PASSWORD=your_dataforseo_password
```

### **5️⃣ Run the Application**
```bash
streamlit run app.py
```

---

## 🏠 Project Structure
```
warmlyv2/
│️── app.py                 # Streamlit UI
│️── ai_functionality.py     # AI logic (OpenAI & DataForSEO)
│️── requirements.txt        # Dependencies
│️── .gitignore              # Ignore sensitive files
│️── .env                    # API Keys (DO NOT COMMIT)
│️── README.md               # Project Documentation
└️── venv/                   # Virtual Environment (Ignored in Git)
```

---

## 🛋️ Dependencies
- **Python 3.8+**
- **Streamlit**
- **OpenAI API**
- **DataForSEO API**
- **LangChain**
- **Requests**
- **Dotenv**

To install them:
```bash
pip install -r requirements.txt
```

---

## 🎯 Usage
- Type `Weather in [City]` to get real-time weather.
- Choose **language** and **AI behavior traits** from the sidebar.
- Chat with the AI assistant and enjoy interactive responses.

---

## 🎨 Screenshots
![WarmlyV2 Screenshot](https://github.com/rahul-vinay/warmlyv2/blob/main/warmlyv2.png?raw=true)


---



