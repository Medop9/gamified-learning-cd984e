# Advanced Algorithms · Zero to Hero Revision Hub

A gamified, single-page revision site for the **Advanced Algorithms** module (EIDIA / UEMF). It takes a complete beginner from "what does a loop cost?" to writing a full singly, doubly and circular linked list in C, and covers every lecture topic, TD exercise and lab exercise in the order a beginner should learn them.

## What's inside

- **World 1 · Complexity (Levels 0–4):** data structures and ADTs, counting operations (TD Part B), growth rates and the formal O/Ω/Θ/o/ω definitions (TD Part A), reading loops (TD Parts C, D3, E plus the lecture traps) and summation-based analysis (TD Parts C4–C5, D, F, G).
- **World 2 · Linked Lists in C (Levels 5–10):** arrays vs linked lists, C pointers (`&`, `*`, `.`, `->`, `malloc`/`free`, `**`), building and traversing lists, every Lab 01 insertion and deletion with a complete `lab01.c`, then doubly and circular lists, including the whiteboard session code.
- **Boss Arena:** two timed 20-point mock exams with model answers and marking tips.
- **Cheat Codes:** three one-page revision sheets for the night before the exam.

Every level follows the same four steps: the concept explained with an everyday analogy, a small syntax example, the challenge from the TD or lab, and a hidden solution with commented C code and its Big O.

Game features: XP per level, ranks and badges saved in the browser (`localStorage`), clickable quizzes, 90-minute exam timers, and an interactive linked-list playground that shows which C lines run for each operation.

## Technology

- One static HTML file (`public/index.html`) with inline CSS and vanilla JavaScript, built on the original Revision Hub skeleton. No build step.
- Whiteboard photos in `public/img/`, served through the Netlify Image CDN (`/.netlify/images`), with a fallback to the original file when opened offline.
- Hosted on Netlify (`netlify.toml` publishes `public/`).

## Run locally

Open `public/index.html` in a browser, or run `netlify dev` to serve it with Image CDN emulation.

## Ideas for later

- Chapters 3–5 of the syllabus (stacks and queues, searching and trees, sorting, graphs) as World 3+, using the same level structure.
