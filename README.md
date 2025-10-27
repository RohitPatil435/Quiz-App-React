# 🎯 Interactive Quiz Application

A dynamic and responsive quiz application built with React.js that provides an engaging user experience with real-time answer validation and visual feedback.

## 🚀 Features

- **Real-time Answer Validation**: Instant feedback with color-coded responses (green for correct, red for incorrect)
- **Smart Navigation**: Question progression with "Next" button that activates after answer selection
- **Answer Locking**: Prevents answer changes after selection to maintain quiz integrity
- **Score Tracking**: Automatic score calculation displayed at quiz completion
- **Reset Functionality**: Retake the quiz anytime with a single click
- **Responsive Design**: Clean and modern UI that works across all devices
- **Smooth Transitions**: CSS animations for enhanced user experience

## 🛠️ Technologies Used

- **React.js** - Frontend framework
- **React Hooks** - useState, useRef for state management
- **CSS3** - Custom styling and animations
- **JavaScript** - Modern JavaScript features

## 📋 Prerequisites

Before running this project, make sure you have:

- Node.js (v14 or higher)
- npm or yarn package manager

## ⚙️ Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/quiz-app.git
```

2. Navigate to the project directory
```bash
cd quiz-app
```

3. Install dependencies
```bash
npm install
```

4. Start the development server
```bash
npm run dev
```

5. Open your browser and visit `http://localhost:5173`

## 📁 Project Structure

```
quiz-app/
├── src/
│   ├── assets/
│   │   └── data.js          # Quiz questions and answers
│   ├── components/
│   │   ├── Quiz.jsx         # Main quiz component
│   │   └── Quiz.css         # Quiz styling
│   ├── App.jsx              # Root component
│   ├── App.css              # App container styles
│   ├── index.css            # Global styles
│   └── main.jsx             # Entry point
├── public/
├── package.json
└── README.md
```

## 🎮 How to Use

1. **Start Quiz**: The app displays the first question automatically
2. **Select Answer**: Click on any of the four options
3. **View Feedback**: Correct answers turn green, incorrect turn red
4. **Navigate**: Click "Next" to move to the next question
5. **View Score**: After the last question, see your total score
6. **Retry**: Click "Reset" to start the quiz again

## 🔧 Customization

### Adding Your Own Questions

Edit the `src/assets/data.js` file:

```javascript
export const data = [
  {
    question: "Your question here?",
    option1: "Option 1",
    option2: "Option 2",
    option3: "Option 3",
    option4: "Option 4",
    ans: 1 // Correct answer number (1-4)
  },
  // Add more questions...
]
```

### Changing Colors

Modify the CSS variables in `src/Quiz.css`:
- `.correct` - Green background for correct answers
- `.wrong` - Red background for incorrect answers
- Button colors and hover effects

## 🎨 Key React Concepts Used

- **State Management** with `useState` hook
- **DOM Manipulation** with `useRef` hook
- **Conditional Rendering** for quiz/result screens
- **Event Handling** for user interactions
- **Component Architecture** for code reusability
- **Array Methods** for dynamic rendering

