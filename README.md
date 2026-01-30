# Dynamic-Quiz-Web-testing

Project Overview

This project demonstrates Selenium automation for a dynamic quiz application developed using HTML, CSS, and JavaScript. The automation validates the complete quiz flow, ensuring the application functions correctly from start to finish. This work was completed as part of the Frugal Testing – Software Engineer assignment.

Features Automated

Launch the quiz application

Verify page URL and title

Start the quiz

Navigate through all quiz questions

Select answers automatically

Submit the quiz

Display and print the final score

Close the browser

Technologies Used

Java

Selenium WebDriver

Maven

IntelliJ IDEA

HTML, CSS, JavaScript

Project Structure QuizAutomation/ ├── src/main/java/com/quiz/automation/ │ └── QuizTest.java ├── pom.xml └── README.md

How to Run

Open the project in IntelliJ IDEA

Ensure Google Chrome is installed

Update the quiz HTML file path in QuizTest.java:

driver.get("file:///C:/path-to-your-quiz/index.html");

Run QuizTest.java as a Java application

Test Scenarios Covered

Verify quiz landing page

Start quiz and load questions

Answer all questions

Submit quiz

Validate final score output

Purpose

This project showcases hands-on experience in UI automation testing, Selenium scripting, and validating real-world web applications.

Author
Syamanth
