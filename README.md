# German Grammar Trainer

A simple, offline-first web application for learning German grammar with intelligent analysis and personalized training recommendations.

## Features

### 📚 Exercise System

- **25 built-in exercises** covering 6 grammar categories:
  - Articles (Artikel)
  - Cases (Kasus)
  - Verbs (Verben)
  - Modal verbs (Modalverben)
  - Separable verbs (Trennbare Verben)
- Multiple question types: fill-in-the-blank, multiple choice, multi-fill
- Three difficulty levels: Basic, Intermediate, Advanced

### 🧠 Smart Learning Analytics

- **Weakness detection**: Automatically identifies problem areas
- **Performance tracking**: Monitors progress across all sessions
- **Personalized recommendations**: Suggests targeted training based on your weak spots
- **Category-wise statistics**: Detailed breakdown by grammar topics

### 🎯 Training Modes

- **Random sessions**: 25 mixed questions from all categories
- **Weakness training**: Focused practice on your weakest areas
- **Progressive training**: Gradually increasing difficulty
- **Mixed training**: Balanced practice across all topics

### 💾 Data Management

- **Offline functionality**: Works entirely in your browser
- **Auto-save**: Progress automatically saved every 30 seconds
- **Session recovery**: Resume interrupted sessions
- **Export data**: Download your learning progress and detailed analysis
- **Import exercises**: Load additional exercise sets from JSON files

### ⌨️ Convenience Features

- **Keyboard shortcuts**:
  - `Ctrl + Enter`: Check current answer
  - `Ctrl + N`: Start new session
  - `Ctrl + R`: Reset current session
- **Real-time scoring**: Live progress tracking
- **Session summaries**: Detailed performance breakdown after each session

## Usage

1. **Setup**: Simply open the HTML file in any modern web browser
2. **Start learning**: Click "Neue Sitzung" (New Session) to begin
3. **Practice**: Answer questions and get immediate feedback
4. **Track progress**: View analytics in the Analysis and Overall tabs
5. **Targeted training**: Use the Targeted tab for personalized recommendations

## Technical Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- No internet connection required (fully offline)

## File Structure

```
german-trainer/
├── index.html          # Main application file
├── script.js           # Application logic (this file)
└── README.md           # This file
```

## Local Storage

All data is stored locally in your browser using localStorage:

- Session history
- Performance statistics
- Learning analytics
- Current session state

## Adding Custom Exercises

Create a JSON file with the following structure:

```json
[
  {
    "id": 26,
    "category": "artikel",
    "difficulty": "basic",
    "type": "fill",
    "question": "Your question here",
    "template": "Sentence with ___ blank",
    "answers": ["correct_answer"],
    "explanation": "Explanation text"
  }
]
```

Then use the file upload feature in the application to import your exercises.

---

**Note**: This is a client-side application designed for personal use. All data remains on your local device.
