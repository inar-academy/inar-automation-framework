Inar Academy Automation Framework
============================

Copyright/Licensing Information : READ LICENSE
---
Project source can be downloaded from : https://github.com/inar-academy/inar-automation-framework.git

Author
--------
Inar Academy

Overview
--------

Welcome to the Inar Academy's Automation Framework repository! This repository is exclusively created for Inar Academy students to explore and learn from a sample automation framework built using Java as the main language, and Selenium, TestNG, and Cucumber as the testing tools for Behavior Driven Testing.

The goal of this framework is to provide a practical example of how to develop a robust and maintainable automation framework using industry-standard tools and best practices. The framework includes sample test cases, page objects, and utility classes to demonstrate the key components, following a page object model design of a functional automation framework.

We encourage all Inar Academy students to use this repository as a learning resource and to experiment with the framework to develop their skills and understanding of automation testing. We welcome feedback, contributions, and suggestions from our students to improve the framework and make it even more useful for the Inar Academy community.

**Please note that this repository is intended for educational purposes only and is not intended for production use.**


Design
--------

Inar Automation Framework is designed to perform UI, API, and backend testing. The framework is built using the Page Object Model design pattern with PageFactory, Singleton Driver, Webdriver Manager, Hooks, Centralized Configuration Data, and Utilities. This document explains the design of the framework in detail.

**Page Object Model**:
Inar Automation Framework uses the Page Object Model design pattern for the automated tests. Each page in the web application has a separate class, which is stored in the "pages" folder. By using the Page Object Model, the test code is separated from the code that defines the elements and actions of each page. This helps in creating an organized and scalable testing framework that can easily adapt to changes in the web application.

**PageFactory Design Pattern**:
PageFactory is used to create object repositories for web application pages. Each page is represented by a Java class with elements and actions mapped using annotations. This design pattern makes it easier to access page objects and maintain tests. It is optimized for use in Selenium WebDriver.

**Singleton Driver**:
The Singleton Driver design pattern uses a single instance of the WebDriver object that is shared between different classes in the test framework. This pattern improves test efficiency by avoiding the overhead of creating multiple WebDriver instances. It also makes it easier to manage the lifecycle of the WebDriver object, ensuring that tests are efficient, reliable, and easy to maintain.

**Webdriver Manager**:
WebDriverManager is used in the framework to save time on browser driver management and improve the reliability of tests. It ensures that the correct driver version is used.

**Hooks**:
A Hook Class is implemented in the framework, containing blocks of code that can be executed at various points in the Cucumber execution cycle. Hooks are commonly used for setting up the environment before each scenario runs and tearing it down after each scenario completes. They provide a convenient and efficient way to automate repetitive setup and teardown tasks, such as initializing test data, starting and stopping a web server, or cleaning up after a test run.

**Centralized Configuration Data**:
The Configuration file is implemented to store important test data, such as usernames, passwords, and other configurations. The Configuration file provides a centralized location for storing and managing this data, making it easy to update and maintain. Storing test data in a Configuration file reduces the amount of hard-coded data in the test code, improving readability and maintainability.

**Utilities**:
A utils package is created in the framework, containing reusable classes like BrowserUtils and DBUtils. These classes provide common functionality that can be used across different parts of the framework, such as interacting with the browser or working with databases. Using these Utilities helps reduce code duplication and improve the efficiency and maintainability of tests.




Tools
--------

The software automation framework is built using various tools and libraries to ensure efficiency and effectiveness. Java 17 is the main language used to develop the framework. Maven is used as the build tool to manage dependencies and run tests from the endpoint as Maven goals, which helps to streamline the process of managing dependencies and running tests.

Selenium WebDriver is a library used for browser automation that allows the automation of browser actions such as clicking buttons, filling out forms, and navigating pages to perform automated tests. Cucumber is used for behavior-driven development (BDD) to specify the expected behaviors of the software in a logical language that anyone can understand. Cucumber runs automated acceptance tests that are written in a behavior-driven development (BDD) style, which streamlines the testing process and ensures that the software meets the expected requirements.

JUnit is used as a unit testing framework for Java that helps write and run automated unit tests, and has been instrumental in the development of test-driven development. Additionally, Extent is used as an open-source reporting library to generate detailed Cucumber HTML reports that are easy for non-technical team members to read and understand. These reports include detailed test steps and screenshots for any test failures that may occur, which helps to identify issues and troubleshoot them quickly. Furthermore, with a small adjustment, the reports can also provide metrics on the percentage of passing, failing, skipped tests, etc.

IntelliJ is used as the integrated development environment (IDE) to develop and test the software automation framework. These tools and libraries have been carefully selected and integrated to ensure that the software automation framework is efficient, effective, and delivers the desired results.

Conclusion
--------

Inar Automation testing framework is a comprehensive tool designed to facilitate software testing for Inar Academy students. With its capabilities for UI, API, and backend testing, this framework enables students to develop a strong foundation in automation testing and enhance their skillset. By providing a user-friendly and efficient platform for testing, Inar Automation testing framework equips students with the necessary knowledge and practical experience to excel in the field of software testing. Overall, this framework is an invaluable resource for Inar Academy students seeking to expand their expertise in automation testing.

