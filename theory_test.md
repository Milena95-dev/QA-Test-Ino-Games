# QA Report - Milena Pereira Torres  
📅 **Date of Test:** 20/05/2025  
🎮 **Game Tested:** Nitropolis 5 - Elk Studios Games  
🖥️ **Test Environment:** Demo Mode on our site  
🌐 **Browser(s) and Device(s):** Mozilla Firefox Version 138.0.4 (64 bits)

###📝 Theoretical Answers

### 1. What is the main objective of Quality Assurance (QA)? 🎯

The main goal of Quality Assurance (QA) is to prevent errors, defects, and failures during the development process, making sure the product meets quality standards before it’s released to users. This involves:

- **Early issue detection:** 🐞 Identifying and reporting bugs as soon as they appear, typically using demand-management tools like Jira or Monday.  
- **Prioritization of critical defects:** Focusing first on problems that could compromise system stability or performance, especially those that might freeze or break the game.

---

### 2. What is the difference between a test case and a test plan? 

**Test Case**  
A test case is a detailed description of a specific scenario created to validate a feature or functionality. It includes:  
- The steps to follow  
- The current (actual) behavior  
- The expected result for that scenario  

**Test Plan**  
A test plan is a comprehensive document defining the overall test strategy. It outlines:  
- Testing objectives and scope  
- Planned timeline and milestones  
- Required resources and tools  
- Any risks and mitigation approaches  

---

### 3. What does the term 'regression testing' refer to? 🔄

Regression testing is a testing technique in which all parts of the product are retested, including every change, previous bug fixes, and mapped test cases, along with code inspections to validate system updates. This ensures full product coverage before delivery or any time changes might impact areas that were already tested. Key aspects include:

- **Complete retesting:** 🔍 Re-executing all relevant test cases, especially those tied to past defects.  
- **Change impact validation:** ✔️ Confirming that new code or fixes haven’t broken existing functionality.  
- **Code inspections:** 👀 Reviewing modified code sections to catch potential issues early.

---

### 4. How would you create a bug report template for software with constant releases? 🐛

To keep reports intuitive, standardized, and concise, I’d include:

- Bug ID (if applicable)  
- Priority (High, Medium, Low – based on labels in our demand-management tool)  
- Device & Browser (e.g., Windows 10 / Chrome 114)  
- Environment & Build Version (e.g., Dev, v2.3.1)  
- Description (clear, to the point)  
- Steps to Reproduce  
  - Step one  
  - Step two  
- Expected Result (what the system should have done)  
- Actual Result (what happened)  
- Attachments (screenshots, videos with audio, logs)

---

### 5. What is the importance of test automation in QA? What would you automate for games with short delivery times? 🤖

Test automation is essential in QA because it speeds up repetitive testing, improves accuracy, and ensures consistent coverage across releases even under tight deadlines. It also allows for automated asset-quality checks and broader validation without manual overhead.

For a game with a rapid release cycle, I’d focus automation on:  
- Core functionality: Page/screen loading, menu navigation, button interactions  
- Calculation & payout accuracy: Verifying bet/win logic remains consistent across builds  
- Performance & stress: Simulating high user load or resource-intensive scenes to catch stability issues  
- Security checks: Automated scans to protect player data and prevent common vulnerabilities
- Tools: For tools, I would use **Cypress** for its ease of setup and excellent support for end-to-end testing, especially in web-based games. It’s great for testing UI interactions and game flows in a fast and reliable way. I also recommend **Playwright** for its powerful cross-browser capabilities. It’s particularly useful when you need to ensure consistency across Chrome, Firefox, and Edge. Both tools are solid choices depending on the project’s complexity and requirements.

---

### 6. What are the main stages of the Software Testing Life Cycle (STLC)? 🔄

- **Requirements Analysis** 📋  
  Analyze project needs to identify functional and non-functional requirements. Plan the tools to be used, estimate testing effort, and evaluate which requirements must be covered.

- **Test Planning** 🗓️  
  Develop the test plan based on time estimates and desired coverage. Define resources (team, tools, infrastructure) and outline the test strategy, prioritizing key objectives.

- **Test Case Design** ✍️  
  Create test cases from the defined requirements, ensuring coverage of main functionalities and workflows within the system’s scope.

- **Test Environment Setup** ⚙️  
  Configure the environment to mirror real-world conditions: install and adjust tools, operating systems, browsers, and any other necessary resources.

- **Test Execution** ▶️  
  Run test cases and log any defects with detailed reproduction steps, severity, and priority. After developers fix issues, perform retests to confirm resolution. This phase concludes once critical and high-priority bugs are addressed.

- **Closure** ✅  
  Evaluate metrics and results, prepare a detailed report of defects and recommendations, document lessons learned, and map out improvements for future testing cycles.

---

### 7. How would you handle a situation where a bug you reported is marked as 'not reproducible' by the development team? ❓

- **Clarify the context:**  
  I’d reach out to the developer or team to understand what environment and configuration they used. Often, differences in OS, browser version or build can prevent reproduction.

- **Verify the environment:**  
  If it seems environment-related, I’d confirm the exact setup from my report (e.g., staging vs. production, specific build number) and ask them to retry under those conditions.

- **Pair testing:**  
  If issues persist, I’d suggest a quick pair-testing session—either in person or via screen share—where we follow my reproduction steps together. This usually uncovers any missing detail or external factor.

- **Supervised reproduction:**  
  If we still can’t reproduce it, I’d run the steps again on my machine with the developer watching, so we can pinpoint the precise moment or condition that triggers the bug.

- **Improve the report:**  
  Regardless of the outcome, I’d review my bug write-up, adding any extra logs, screenshots, or clarifications needed to make it as clear and complete as possible for future reference.
