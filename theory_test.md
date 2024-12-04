**General Questions**

**1\. What is the primary purpose of Quality Assurance (QA)?**

The primary purpose of Quality Assurance (QA) is to prevent errors, defects, and failures during the software development process, ensuring that the product meets quality standards before being delivered to customers. This includes identifying and reporting problems as soon as they are found, using demand management platforms like Jira or Monday, and prioritizing critical issues that could compromise the system’s functionality or stability, such as failures that could freeze or break the game.

**2\. What is the difference between a test case and a test plan?**

A test case is a detailed description of a specific test designed to validate a feature or functionality. It includes the steps to be followed, the current behavior of the software, and the expected results for that scenario.

On the other hand, a test plan is a comprehensive document that defines the overall test strategy. It outlines the objectives to be achieved, the scope of testing, the planned timeline, and the resources and tools needed for the effective execution of all tests.

**3\. What does the term 'regression testing' refer to?**

Regression testing is a testing technique in which all parts of the product are tested, including every change, previous bug, and mapped test case, along with code inspections to validate possible system changes. This ensures complete product coverage before delivery to the customer or after changes that may impact parts of the system that were previously tested.

**4\. How would you create a template to describe bugs on a software that is being constantly released?**

I would imagine a template that is intuitive, standardized, and concise:

* Include the bug ID (if used);  
* Priority (considering a demand app, I would choose one from the label like (High, Medium, Low)  
* I also usually use the device and browser used for the tests;  
* Environment being tested and build version used for testing;  
* A brief, intuitive, and easy-to-read description of the issue;  
* Detailed steps to reproduce;  
* Expected result (what the system should have done);  
* Attachments at the end, including screenshots and videos with active audio;

**5\. What is the importance of test automation in QA? What would you explore in terms of automation for games being developed in a short period of time?**

Test automation is crucial in QA as it significantly reduces the time required to perform repetitive tests and increases the reliability and efficiency of the validation process. It also enables asset quality evaluation and broader test coverage, ensuring system quality even under tight deadlines.

For games developed in a short time frame, I would explore:

* Basic functionality tests, such as page loading, usability, and button functionality  
* Validation of calculations and payouts, ensuring consistency in winnings and bets  
* Performance and stress tests, simulating heavy loads to check stability  
* Security tests to protect sensitive player information

**6\. Describe the main stages of the Software Testing Life Cycle (STLC).**

* **Requirements Analysis**: At this stage, the project needs are analyzed to identify functional and non-functional requirements. Tools to be used are planned, time estimations for testing are made, and the requirements that need to be met are evaluated.

* **Test Planning**: Here, the test plan is created based on estimated time and desired coverage. Necessary resources like team, tools, and infrastructure are defined, and the test strategy is developed, prioritizing the main objectives.

* **Test Case Design**: Test cases are created based on the defined requirements. This stage includes the creation of cases that cover the system's scope, ensuring that main functionalities and workflows are tested.

* **Test Environment Setup**: In this phase, the test environment is set up to simulate real-world conditions. This includes installing, adjusting, and configuring tools, operating systems, browsers, and other necessary resources.

* **Test Execution**: Test cases are executed, and any defects found are recorded in detail, including reproduction steps, severity, and priority. After fixes are made by the development team, a retest is conducted to ensure issues are resolved. This phase ends when critical and high-priority bugs are fixed.

* **Closure**: After test execution, metrics and results are evaluated. Detailed reports listing defects found and suggested improvements are prepared. Additionally, lessons learned are documented, and future test cases that can optimize future processes are mapped.

**7\. How would you handle a situation where a bug you reported is marked as 'not reproducible' by the development team?**

First, I would contact the developer or the team responsible for the attempt to reproduce to understand any difficulties faced, such as differences in the test environment or configurations used. If it’s determined that the issue is environment-related, I would suggest they try reproducing the bug in the correct environment specified in the report.

If this approach doesn’t resolve the issue, I would suggest conducting a pair testing session (in-person or virtual) with the team, reviewing the steps described in my report to identify any gaps or external factors that might affect reproducing the bug.

If we manage to reproduce the bug during the session, I would leave the correction to the development team, offering support if they need more information or suggestions. However, if the issue persists, I would try reproducing the bug again on my machine under their supervision, to explore the exact conditions in which the error occurs.

Regardless of the outcome, I would review my report to identify possible improvements in the bug description, ensuring it is as intuitive, detailed, and complete as possible to avoid future confusion.
