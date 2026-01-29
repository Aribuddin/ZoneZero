# ZoneZero AI Research Assistant

An intelligent AI-powered research assistant using Google Gemini and Firebase.

##  Features

- **AI Research** - Ask questions, get AI-generated answers with citations
- **PDF Upload** - Upload PDFs and ask questions about them
- **Image Analysis** - Upload images and get AI descriptions
- **User Authentication** - Secure login/signup with Firebase
- **Search History** - Track all your searches (user-specific)
- **Cloud Storage** - Data stored in Firebase Cloud

##Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python Flask
- **Database:** Firebase Realtime Database
- **AI:** Google Gemini API
- **Authentication:** Firebase

##  Local Setup

1. **Clone the repository:**
```bash
   git clone https://github.com/Aribuddin/ZoneZero.git
   cd ZoneZero
```

2. **Create `.env` file** with your Gemini API key:
```
   GEMINI_API_KEY=your_api_key_here
```

3. **Add `serviceAccountKey.json`** from Firebase Console

4. **Install dependencies:**
```bash
   pip install -r requirements.txt
```

5. **Run the application:**
```bash
   python app.py
```

6. **Open in browser:**
```
   http://localhost:5000
```

##  Usage

1. **Sign up** with your email
2. **Ask a question** in the search box
3. **Get AI-generated answer** with citations
4. **Upload files** (PDF/images) for analysis
5. **Check history** to see all your searches

##  How It Works

### Frontend (HTML/CSS/JavaScript)
- User interface for asking questions
- Upload file functionality
- Display AI-generated answers

### Backend (Python Flask)
- Receives questions from frontend
- Calls Google Gemini API
- Saves search history to Firebase
- Returns formatted responses

### Database (Firebase)
- Stores user accounts
- Stores search history per user
- Real-time data synchronization

### AI (Google Gemini)
- Processes natural language questions
- Generates intelligent responses
- Analyzes documents and images

##  Project Structure
```
ZoneZero/
├── app.py              # Backend Flask application
├── index.html          # Frontend HTML
├── .gitignore          # Git ignore rules
├── requirements.txt    # Python dependencies
└── uploads/            # User uploaded files (local only)
```

##  Important Files (Not Included)

These files are in `.gitignore` for security reasons:
- `.env` - Your Gemini API keys
- `serviceAccountKey.json` - Firebase credentials

Keep these files locally and never push to GitHub!

##  Creator

**MD.Aribuddin**
- 🎓 Education: CSE at CMREC (CMR Engineering College)
-  Connect: [@md_aribuddin_21](https://instagram.com/md_aribuddin_21)


Made with ❤️ by Aribuddin
