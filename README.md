# German Grammar Trainer

A simple, offline-first web application for learning German grammar with intelligent analysis and personalized training recommendations.

## 🌐 Live Demo

**Try it now:** [https://austinchen123.github.io/German-A1-practice/](https://austinchen123.github.io/German-A1-practice/)

## 📥 How to Use

### Option 1: Online Version (Recommended)

- Visit the live demo link above
- Works in any modern web browser
- No download required
- All features available immediately

### Option 2: Offline Version

1. Download the repository files from [GitHub](https://github.com/austinchen123/German-A1-practice)
2. Open `index.html` in your web browser
3. Works completely offline after download
4. Perfect for areas with limited internet access

## 📚 Exercise Database

### Built-in Exercises

- **25 basic exercises** included by default
- Covers fundamental A1 grammar concepts
- Ready to use immediately

### Extended Exercise Set (Recommended)

For a comprehensive learning experience, download the additional exercise database:

1. **Download exercises**: Go to the [repository](https://github.com/austinchen123/German-A1-practice) and download `questions.json`
2. **Load in app**: Use the "📁 Datei laden" (Load File) button in the application
3. **Import**: Select the downloaded `questions.json` file
4. **Enjoy**: Access 200+ additional exercises across all grammar categories

**File location**: `questions.json` in the repository root

## Features

### 📚 Exercise System

- **25+ built-in exercises** covering 6 grammar categories:
  - Articles (Artikel)
  - Cases (Kasus)
  - Verbs (Verben)
  - Modal verbs (Modalverben)
  - Separable verbs (Trennbare Verben)
  - Possessive pronouns (Possessivpronomen)
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

## 🚀 Quick Start Guide

1. **Access the app**: Use online version or download for offline use
2. **Load exercises** (recommended): Download and import `questions.json` for 200+ additional questions
3. **Start learning**: Click "Neue Sitzung" (New Session) to begin
4. **Practice**: Answer questions and get immediate feedback
5. **Track progress**: View analytics in the Analysis and Overall tabs
6. **Targeted training**: Use the Targeted tab for personalized recommendations

## 🔄 Loading Additional Exercises

### Step-by-step:

1. Visit the [repository](https://github.com/austinchen123/German-A1-practice)
2. Click on `questions.json`
3. Click the "Download" button (or right-click "Save As...")
4. In the application, click "📁 Datei laden" button
5. Select the downloaded `questions.json` file
6. Exercises will be automatically imported and available for practice

## Technical Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- No internet connection required (fully offline after initial load)

## File Structure

```
german-trainer/
├── index.html          # Main application file
├── questions.json      # Extended exercise database
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
{
  "exercises": [
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
}
```

Then use the file upload feature in the application to import your exercises.

## 🎯 Grammar Categories Covered

- **Articles**: der, die, das, ein, eine (definite and indefinite articles)
- **Cases**: Nominativ, Akkusativ, Dativ, Genitiv
- **Verbs**: Conjugation, reflexive verbs, strong/weak verbs
- **Modal verbs**: können, müssen, dürfen, sollen, wollen, mögen
- **Separable verbs**: aufstehen, ankommen, einkaufen, etc.
- **Possessive pronouns**: mein, dein, sein, ihr, unser, etc.

## 🤝 Contributing

Feel free to contribute additional exercises or improvements:

1. Fork the repository
2. Add new exercises to `questions.json`
3. Test the exercises in the application
4. Submit a pull request

## 📄 License

This project is open source and available under the MIT License.

---

**Note**: This is a client-side application designed for personal learning. All data remains on your local device and is not transmitted anywhere.
