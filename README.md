# 🎨 Emotion-to-Vibe Generator

A customized design web app that takes your mood or emotion and transforms it into:

- 💬 Poetic vibe phrases  
- 🎨 A custom color palette  
- 🖼️ A moodboard image gallery  

This is a creative playground that makes your feelings visible.

## ✨ Demo
Coming soon...

## 🛠️ Project Structure
```text
emotion-to-vibe/
├── backend/
│   └── app.py
├── frontend/
│   ├── App.jsx
│   ├── components/
├── .env
├── README.md
├── .gitignore
```

## 🐍 Setting Up the Python Backend (FastAPI)

Follow these steps to get the backend running locally:

```bash
# 1. Navigate into the backend directory
cd backend

# 2. Create a virtual environment (this creates a 'venv/' folder)
python3 -m venv venv

# 3. Activate the virtual environment
# On macOS/Linux:
source venv/bin/activate

# On Windows (Command Prompt):
venv\Scripts\activate

# 4. Install Python dependencies
pip install -r requirements.txt

# 5. Add environment variables
cp .env.example .env
# Then open '.env' and fill in your API keys for OpenAI and Unsplash

# 6. Run the FastAPI backend server
uvicorn app:app --reload --port 5001
```

## 🧠 Powered By
- OpenAI API
- Unsplash API
- FastAPI
- React
- Tailwind CSS

---

🤍 Attribution
Wanted to create something that combines emotion, technology, and design. 
As AI and technology becomes more human, we become less human. How can we bring back emotion to technology?

📜 License
MIT — feel free to use, remix, and build on it.
