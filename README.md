# 🎯 Quizzler - The Quiz App

Quizzler is a GUI-based quiz application built with Python. It fetches trivia questions from the Open Trivia Database API and presents them in a clean, interactive interface using `tkinter`.

---

## 🚀 Features

- ✅ 20 random True/False questions from the *Science: Computers* category
- ✅ Live score tracking
- ✅ Color-coded feedback (Green = Correct, Red = Wrong)
- ✅ Automatic question transitions
- ✅ Clean and responsive UI with `tkinter`

---

## 🛠️ Tech Stack

- **Python 3**
- **Tkinter** – for building the GUI
- **Open Trivia DB API** – for fetching quiz questions
- **html module** – to decode special characters in the questions

---

## 📁 File Structure

├── data.py # Fetches questions from the API
├── main.py # Main driver that sets up the quiz
├── question_model.py # Models each question with text and answer
├── quiz_brain.py # Handles quiz logic, score tracking, answer checking
├── ui.py # Creates the GUI and manages interaction
├── images/
│ ├── true.png # Image for "True" button
│ └── false.png # Image for "False" button

---

## ▶️ How to Run

1. **Install Python** (if not already):  
   [https://www.python.org/downloads](https://www.python.org/downloads)

2. **Clone the repository or download the ZIP**:

   ```bash
   git clone https://github.com/yourusername/quizzler.git
   cd quizzler

3. **Run the App:**:
   python main.py

## 🌐 API Used
- Open Trivia DB – Free trivia questions API

## 📌 Future Ideas
- Add difficulty levels and question categories
- Multiple-choice questions
- High score board
- Sound effects and animations

## 🧠 Made By
- Arya Madiwale
