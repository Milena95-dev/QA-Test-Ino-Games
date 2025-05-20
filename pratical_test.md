# 🎮 QA Game Test Report – *Nitropolis 5* by Elk Studios

**QA Analyst:** Milena Pereira Torres  
**Date of Test:** 20/05/2025

---

## 🧪 Functional Testing – Detailed Validation

| **Criteria**                                                                             | **Result**          | **Comments**                                                                                       |
|------------------------------------------------------------------------------------------|---------------------|----------------------------------------------------------------------------------------------------|
| Game loads properly on different browsers (Chrome, Firefox, Edge, Opera GX)             | ✅ Passed            | The game loaded successfully on all tested browsers. Average loading time: **4.7s–6.2s**.         |
| Buttons and controls (spin, bet, autoplay) work as expected                             | ✅ Passed            | All buttons were functional and responsive. No broken interactions found.                          |
| Bet variations calculate winnings correctly                                              | ✅ Passed            | Multiple bet amounts tested (€0.20 to €50.00). Winnings were accurately calculated and displayed. |
| Bonus features trigger and function correctly                                            | ✅ Passed            | All tested features (e.g., Buy Feature, Free Spins) activated and ran as expected.                |
| Animations and graphics display correctly without glitches                              | ✅ Passed (minor)    | Minor flickering occurred on **Edge** during transitions. No major bugs.                          |

---

## 🌐 Cross-Browser Testing Summary

| **Browser** | **Version** | **Loading Time** | **Buttons Work?** | **Payment (based on bet)** | **Bet Amounts Tested (€)**       | **Bonuses Work?** | **Animations OK?** | **Graphics OK?**              |
|------------|-------------|------------------|-------------------|-----------------------------|----------------------------------|-------------------|--------------------|-------------------------------|
| Firefox    | 125.0       | 6.2s             | ✅ Yes            | €0.40 → Won €1.60           | 0.20, 2.00, 20.00                | ✅ Yes            | ✅ Yes             | ✅ Yes                        |
| Chrome     | 124.0       | 4.7s             | ✅ Yes            | €10.00 → Won €5.00          | 0.60, 6.00, 40.00                | ✅ Yes            | ✅ Yes             | ✅ Yes                        |
| Edge       | 123.0       | 5.1s             | ✅ Yes            | €20.00 → Won €35.00         | 1.00, 10.00, 50.00               | ✅ Yes            | ✅ Yes             | ⚠️ Minor flickering (transitions) |
| Opera GX   | 109.0       | 5.9s             | ✅ Yes            | €0.60 → Won €0.20           | 0.40, 4.00, 30.00                | ✅ Yes            | ✅ Yes             | ✅ Yes                        |

---

## 🐞 Issue Reports

Bug documentation is available in the following locations:

- 📁 [**QA Issues Reported** – Google Drive](#)
- 📘 [**Ino Games Test Repository** – GitHub](#)

All issues include:

- Steps to reproduce  
- Expected vs. actual results  
- Severity level (Minor, Major, Critical)  
- Supporting screenshots or videos (when applicable)

---

## ✅ Submission Notes

All findings were compiled in both document and visual format for clarity. Reports were organized and structured to reflect:

- Functional testing results  
- Bug report templates  
- Suggestions for improvement

---

## 🧠 General Overview

### 🎮 Why did I choose *Nitropolis 5*?

> The game stands out for its **impressive visuals** — it has excellent graphic quality with smooth and entertaining animations. However, the **audio lacks responsiveness**, becoming unpleasant over time, and the **UI design is somewhat confusing**, which negatively impacts the overall experience.

### 🔁 Would I play it again?

> **Honestly, no.** I had to mute the audio entirely to finish the test due to its repetitiveness and discomfort. The animations became visually overwhelming with prolonged exposure. Additionally, the **Buy Feature menu** is hard to read, making it difficult to understand the available bonus options.

### 🧩 Was this an engaging experience?

> To some extent, yes. It’s always engaging to explore new types of games, especially in the **slot genre**. I was already familiar with the company through other titles I enjoy more. Testing this lesser-known game helped me understand **why it hasn't gained as much popularity**.

---

*Thank you for reviewing this QA test report. Feel free to explore the related documentation or reach out for clarification.*
