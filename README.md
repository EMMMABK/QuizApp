# Quiz App


## Features

- **Dynamic Questions and Options**: The app supports an array of questions with multiple-choice options.
- **Instant Feedback**: Users receive immediate feedback on their selected answers.
- **Interactive UI**: Clean and responsive interface with clickable options.
- **State Management**: Efficient state handling for user progress and question navigation.

## Technologies Used

- React.js
- JavaScript (ES6+)
- CSS for styling

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/EMMMABK/QuizApp.git
   ```
2. Navigate to the project directory:
   ```bash
   cd quiz-app
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```
5. Open your browser and go to `http://localhost:3000` to view the app.

## Screenshots
![quiz1](/assets/quiz1.png)
![quiz1](/assets/quiz2.png)
![quiz1](/assets/quiz3.png)
![quiz1](/assets/quiz4.png)
![quiz1](/assets/quiz5.png)
![quiz1](/assets/quiz6.png)
![quiz1](/assets/quiz7.png)

## Project Structure
```
quiz-app/
├── public/
├── src/
│   ├── components/
│   │   └── Quiz.jsx        # Main Quiz component
|   |    ── Quiz.css       # Styling for the app      
│   ├── assets/
│   │   └── data.js # Sample question data
│   ├── App.js           # Root component
│   ├── index.js         # React entry point
│
├── package.json
└── README.md
```

## Usage

1. Customize the question data in `src/assets/data.js`.
2. Update the styles in `src/Components/Quiz.css` for a personalized look.
3. Run the app to test your quiz.

## Example Question Data

The questions are stored in `src/assets/data.js` and follow this structure:

```javascript
const data = [
  {
    question: "What is the capital of France?",
    options: ["Paris", "London", "Berlin", "Madrid"],
    correct: 1,
  },
  {
    question: "Which programming language is used for web development?",
    options: ["Python", "JavaScript", "C++", "Java"],
    correct: 2,
  },
];

export default data;
```

## Contributing

Contributions are welcome! If you'd like to improve the app or fix a bug, feel free to:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push the branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it as per the license terms.
