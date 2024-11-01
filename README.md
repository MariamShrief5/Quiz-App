#### Quiz App
Quiz App is a customizable online testing platform allowing users to test their knowledge across different subjects, difficulty levels, and question numbers. Designed for students, professionals, and anyone eager to learn, Quiz App offers a tailored experience for a variety of knowledge fields. Built with HTML, CSS, and JavaScript, the app is structured for easy navigation, engaging design, and immediate feedback on performance.

### Project Description
Quiz App is a user-focused application where participants can select their desired subject, difficulty level, and number of questions for a quiz. Using JavaScript for logic and an API to fetch questions, the app evaluates the user’s responses and provides a final score. The responsive HTML and CSS layout ensures compatibility across devices, making it ideal for both casual and serious test-takers.

### Project Details
1. **User Interface**
   - **Design**: A clean, intuitive layout where users can easily select topics, levels, and customize question count.
   - **Styling**: CSS is used for a responsive, visually appealing design.

2. **Functionality**
   - **Question Fetching**: The app fetches questions from an API based on selected criteria.
   - **Answer Submission**: Users can submit answers, which are evaluated to calculate the score.
   - **Score Display**: Upon completion, the app displays the user's score and feedback.
   - **API Integration**: Uses a quiz-based API to retrieve questions dynamically, enhancing the variety and relevance of the quiz content.

3. **Object-Oriented Design (OOP)**
   - **Classes**: 
     - `Quiz`: Manages question fetching, storing, and the quiz flow.
     - `Question`: Represents individual questions, stores options and correct answers.
     - `User`: Manages user selections and tracks scores.
   - **Encapsulation**: Core functionalities (like answer validation) are wrapped within classes for better structure and future scalability.
   - **Inheritance**: Could be extended to support different types of quizzes (e.g., timed quizzes) by inheriting from base classes.
---
### Example Usage
1. User selects **Science** as the quiz topic.
2. Chooses **Intermediate** level.
3. Sets **10 questions** for the quiz.
4. Completes the quiz and views the score along with correct answers.
---
### Tools and Technologies:
- **HTML**: Layout structure.
- **CSS**: Styling and responsive design.
- **JavaScript**: Logic handling, API requests, and interactivity.
- **API**: Fetches question data dynamically.

