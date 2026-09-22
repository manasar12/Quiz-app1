 Quiz App

A simple, interactive quiz application built with vanilla HTML, CSS, and JavaScript. It presents multiple choice questions with a countdown timer, visual progress bar, and immediate feedback on selection. The app is contained in a single HTML file and requires no build tools or dependencies.


 Overview
This Quiz App was created to demonstrate core frontend development skills: DOM manipulation, event handling, state management, and responsive design. It includes a timer for each question, a progress bar to show quiz completion, and highlights the selected answer. The quiz data is stored in an array of objects, making it easy to add or modify questions.

 Features
 Multiple choice questions – four questions about web development basics.
 Countdown timer – 15 seconds per question; auto advances when time runs out.
 Progress bar – visually indicates how far you are in the quiz.
 Selected option highlighting – the chosen answer is highlighted in blue.
 Score calculation – final score displayed at the end.
 Responsive layout – cantered card design that works on different screen sizes.
 No dependencies – pure vanilla JavaScript, HTML, and CSS.

 Tech Stack
 HTML5 
 CSS3
 JavaScript  


 How to Run
1. Clone or download the repository.
2. Open index.html in any modern web browser.
3. That's it! The quiz will start immediately.

No server, build step, or installation is required.

 Code Structure
The entire application resides in a single index.html file:

 <head> – contains meta tags, title, and embedded CSS.
 <body> – holds the quiz container with:
   Question text
   Timer display
   Progress bar
   Options container (populated dynamically)
   Next button
   Result area
 <script> – contains:
   quizData array – questions, options, and answers.
   State variables – currentQuestion, score, timeLeft, timer, selectedOption.
   Functions – loadQuestion(), selectOption(), checkAnswer(), nextQuestion().
   Initial call to loadQuestion().

 Key Concepts Demonstrated
 DOM Manipulation: Creating elements dynamically, updating text and styles.
 Event Handling: Inline onclick and programmatic event listeners.
 State Management: Tracking current question, score, timer, and selected option.
 Timers: Using setInterval and clearInterval for the countdown.
 Template Literals: String interpolation with ${}.
 CSS Transitions: Smooth hover and selection effects.
 Flexbox: Centering the quiz card on the page.
 Block Scoping: Using let and const appropriately.

 Future Enhancements
 Randomize questions – shuffle the order each time.
 Add more questions – easily extend quizData.
 Local storage – save high scores.
 Accessibility – add ARIA attributes and keyboard navigation.
 Animations – fade in/out between questions.
 Category selection – allow users to choose quiz topics.
 Backend integration – fetch questions from an API


Created as a portfolio project to demonstrate fundamental web development skills.
