# internship-

📝 Quiz App with Login
This is a simple, single-page Quiz Application built using HTML, CSS, and pure JavaScript. It features a basic login mechanism and a multiple-choice quiz interface, calculating the user's score at the end.

🚀 Features
User Login: A basic form to enter an email and password.

Simple client-side validation for required fields and minimum password length (6 characters).

User details are saved locally using localStorage to simulate a session (no real backend authentication).

Multiple-Choice Quiz: Presents a set of predefined questions and options.

Instant Feedback: Highlights the correct and incorrect answers immediately after an option is selected.

Scoring System: Tracks the user's score based on correct answers.

Result Screen: Displays the final score out of the total number of questions.

Restart Functionality: Allows the user to reset the score and start the quiz over.

Responsive Design: Styled using basic CSS for a clean, centered interface.

🛠️ Technology Stack
HTML5: Structure of the web page.

CSS3: Styling for layout and appearance.

JavaScript (ES6+): Core logic for the login, quiz flow, scoring, and DOM manipulation.
⚙️ How to Run
Since this is a client-side application with no backend dependencies, you can run it easily:

Save the Code: Save the provided HTML content as index.html.

Open in Browser: Double-click the index.html file, or right-click and choose "Open with" your preferred web browser (Chrome, Firefox, etc.).

💡 Usage
Login Screen: Enter an email and a password (minimum 6 characters) and click Login. The login form will hide, and the quiz will appear.

Quiz Screen:

Read the question.

Click on one of the options to select your answer.

The chosen option and the correct answer will be highlighted.

Click the Next button to proceed to the next question.

Result Screen: After the last question, the result screen will appear, showing your score. Click Restart Quiz to play again.

🔑 Key JavaScript Concepts
quizData Array: Stores the questions, options, and correct answers.

DOM Manipulation: Uses methods like document.getElementById(), innerText, innerHTML, classList.add/remove, and createElement() to interact with the page elements.

Event Listeners: Used extensively for handling button clicks (loginBtn, nextBtn, restartBtn) and option selections (selectOption function).

localStorage: Used to store a simulated user session after a successful login.

State Management: The currentQuestion and score variables track the user's progress through the quiz.
