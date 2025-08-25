# 迴圈終結者 / Break the Cycle
### An Action Angel First-Aid Station 💖

*A submission for the HackVerse hackathon.*


*Pictured: The default "Cute Angel" mode.*

---

### Table of Contents
1.  [About the Project](#about-the-project)
2.  [The Problem It Solves](#the-problem-it-solves)
3.  [Live Demo](#live-demo)
4.  [Key Features](#key-features)
5.  [Screenshots](#screenshots)
6.  [Tech Stack](#tech-stack)
7.  [How to Run](#how-to-run)
8.  [HackVerse Submission Details](#hackverse-submission-details)

---

### About the Project

**Break the Cycle** is a single-page web application designed as a mental health first-aid tool. It provides immediate, actionable support for individuals caught in cycles of overthinking, procrastination, and negative self-talk.

Instead of offering generic advice, it gamifies the process of taking the first step. The central metaphor of "taking an action pill" reframes commitment as a simple, concrete action, helping users build momentum and break free from mental inertia.

---

### The Problem It Solves

This tool was built to address two common but debilitating mental states:

*   **Analysis Paralysis:** The state of over-analyzing a situation so much that a decision or action is never taken. This is often driven by a fear of making the wrong choice or failing to be perfect.
*   **Trauma Loops:** The experience of replaying negative past events or intrusive thoughts, leading to a feeling of hopelessness and the belief that effort is pointless.

Both states result in inaction and a sense of being stuck. This application serves as a pattern interrupt to break that cycle.

---

### Live Demo

**[➡️[liink!](https://tokinosuna.github.io/action-angel-first-aid-station/)]** 
*(Replace this with your actual GitHub Pages link after deploying)*

---

### Key Features

*   💊 **The Action Pill:** A core mechanic where users write down one micro-task to commit to, turning an overwhelming problem into a single, manageable step.
*   🎭 **Dual Personalities:** Switch between two modes to match your mood:
    *   **Cute Angel:** Provides sweet, gentle, and overwhelmingly positive encouragement.
    *   **Grumpy Angel:** Offers brutally honest, tough-love motivation to give you the kick you need.
*   💬 **Interactive Cheer Squad:** A chat window that provides instant, dynamic feedback. When you take an "Action Pill," the bot responds with a burst of three unique, encouraging messages.
*   ✨ **Celebratory Feedback:** Successful actions are celebrated with a burst of on-screen confetti, providing a satisfying dopamine hit.
*   🌐 **Bilingual Support:** Fully translated into both **English** and **Traditional Chinese**.
*   💾 **Persistent State:** The app uses `localStorage` to remember your chosen theme, language, and chat history for a seamless return experience.
*   🚀 **Performant & Lightweight:** Built with vanilla JavaScript, it's fast, responsive, and has zero dependencies. Chat history is capped to ensure the application remains snappy over time.

---

### Screenshots

| Cute Angel Mode (Default) | Grumpy Angel Mode |
| :---: | :---: |
|  |  | 
*(You can create a screenshot for the Grumpy Mode to add here)*

---

### Tech Stack

*   **HTML5:** For the core structure and content.
*   **CSS3:** For styling, layout (Flexbox & Grid), and dynamic theming using CSS Variables.
*   **Vanilla JavaScript (ES6+):** For all application logic, interactivity, DOM manipulation, and state management.
*   **`localStorage` API:** For persisting user settings and chat history across sessions.

---

### How to Run

This is a static web project with no build process required.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```
2.  **Navigate to the directory:**
    ```bash
    cd your-repo-name
    ```
3.  **Open the `index.html` file in your favorite web browser.**

That's it!

---

### HackVerse Submission Details

This project was built from scratch during the HackVerse hackathon period. It aligns with the judging criteria as follows:

*   **Innovation:** The dual-personality system (Cute/Grumpy) is a novel approach to personalized motivation. The "Action Pill" metaphor provides a unique and creative solution to the abstract problem of mental inertia.
*   **Technical Execution:** The application is built entirely with clean, well-organized vanilla JavaScript, demonstrating strong foundational skills. The use of CSS variables for instant, efficient theming and `localStorage` for state persistence shows a thoughtful approach to front-end architecture. The code is self-contained in a single file for simplicity.
*   **Impact:** This tool has significant potential for real-world application. It addresses a common and serious mental health challenge in an accessible, destigmatized, and fun way. It provides users with a tangible tool they can use in moments of distress to improve their well-being.
*   **Presentation & User Experience (UX):** The project features a cohesive and charming pixel-art aesthetic. The user flow is simple and intuitive. The instant, multi-message feedback and confetti create a rewarding and engaging experience that encourages repeated use.

---
**Code Without Limits.**
