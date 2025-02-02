# simple_Quiz_Application
simple Quiz application with python
Welcome to the Quiz Application! This application is designed to help students test their knowledge by answering multiple-choice questions. After completing the quiz, you can generate a performance report to review your results.

#Features
Interactive Quiz:

Answer multiple-choice questions.

Navigate through questions using the "Next" button.

Performance Tracking:

Your score is calculated based on correct answers.

A performance report is generated after the quiz.

Report Generation:

Save your quiz results as a text file on your desktop.

The report includes:

Your name.

Total number of questions.

Your score.

Performance evaluation (e.g., "Excellent", "Good", or "Needs Improvement").

User-Friendly Interface:

Simple and intuitive design.

Clear instructions and feedback.

#How to Use
1. Start the Application
Run the program.

Enter your name when prompted.

2. Answer Questions
Read each question carefully.

Select one of the three options using the radio buttons.

Click the "Next" button to proceed to the next question.

3. View Results
After answering all questions, your score will be displayed.

Click the "Generate Report" button to save your performance report.

4. Generate Report
A text file named performance_report.txt will be saved to your desktop.

Open the file to review your results.
Example Report
If you score 3/4, the generated report (performance_report.txt) will look like this:
User: hadeel adel
Total Questions: 4
Score: 3/4
Performance: Good

#Requirements
Python 3.x installed on your system.

MySQL Database:

A database named question_db.

A table named question with the following columns:

id (Primary Key)

Q_value (Question text)

chose_1 (Option 1)

chose_2 (Option 2)

chose_3 (Option 3)

correct_option (Correct option: A, B, or C)

A table named score_db to store user scores:

id (Primary Key)

name (User name)

score_value (User score)
