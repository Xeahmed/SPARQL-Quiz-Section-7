# SPARQL Quiz - Section 7

## Overview

This project is an interactive, web-based quiz designed for Section 7 of the Semantic Web course at the Egyptian E-Learning University (EELU), Sohag branch. The quiz focuses on **SPARQL** (SPARQL Protocol and RDF Query Language), covering topics such as its definition, purpose, query types (SELECT, ASK, CONSTRUCT, DESCRIBE), basic syntax, and practical examples applied to a university ontology. It serves as an educational tool to help students assess their understanding of the lecture material in an engaging, user-friendly format.

Created by **Eng: XE Ahmed Refat**, a student at EELU Sohag branch, this quiz is hosted on GitHub Pages for easy access and is designed to be lightweight, responsive, and visually appealing. The project was developed with assistance from **Grok**, an AI tool created by xAI, ensuring high-quality question generation and technical implementation.

## Purpose

The primary purpose of this quiz is to:
- Reinforce students' understanding of SPARQL concepts taught in Section 7.
- Provide an interactive platform for self-assessment with immediate feedback.
- Enhance learning through a balanced mix of multiple-choice and true/false questions across Easy, Medium, and Hard difficulty levels.
- Offer a bilingual experience with questions in English and explanations in Egyptian Arabic to cater to EELU students.

The quiz is intended for students, instructors, and anyone interested in SPARQL, RDF, and the Semantic Web, providing a practical way to test knowledge and identify areas for improvement.

## Features and Implementation

The quiz is implemented as a single HTML file (`quiz_section7.html`) with inline CSS and JavaScript, ensuring no external dependencies and compatibility with modern browsers. Key features include:

- **Responsive Design**: Optimized for phones (≤480px), tablets (≤768px), and desktops using Flexbox and media queries.
- **Visual Aesthetics**: Gradient background (light gray to white for light mode, dark gray to black for dark mode), rounded corners, box shadows, and clean typography (Arial).
- **Animations**: Fade-in effect for questions and a bounce animation for the submit button.
- **Dark Mode**: Toggle button to switch between light and dark themes for user comfort.
- **Progress Bar**: Displays quiz completion percentage, updating dynamically.
- **Question Format**: 20 multiple-choice questions (MCQs) with 4 options and 15 true/false questions, covering all major lecture topics.
- **Feedback System**: Immediate feedback (green for correct, red for wrong) with detailed explanations in Egyptian Arabic (RTL), using technical terms in English.
- **Final Evaluation**: Displays total score, percentage, and performance feedback in Egyptian Arabic (e.g., "ممتاز!" for ≥80%).
- **Special Character Handling**: Uses an `escapeHTML` function to safely display URIs (e.g., `<http://example.org/>`) and code snippets (e.g., `SELECT ?student ?name`).
- **Accessibility**: Bilingual interface (English questions, Arabic explanations) with RTL support for Arabic text.

The quiz was carefully designed to ensure balanced answer distributions (5 MCQs per option A/B/C/D; 8 True/7 False) and comprehensive coverage of the lecture content, including SPARQL basics, query types, and university ontology examples.

## Technical Details

- **File**: `quiz_section7.html`
- **Technologies**: HTML, CSS (Flexbox, media queries), vanilla JavaScript
- **Dependencies**: None, ensuring lightweight deployment
- **Hosting**: Deployed on GitHub Pages for accessibility
- **License**: MIT License (see below)

The implementation prioritizes simplicity, performance, and user experience, making it suitable for educational environments and easy to deploy on platforms like GitHub Pages or Netlify.

## Contact

For questions, feedback, or collaboration, please contact:

- **Name**: Eng: XE Ahmed Refat
- **Email**: [a.xp2121@gmail.com](mailto:a.xp2121@gmail.com)
- **GitHub**: [github.com/Xeahmed](https://github.com/Xeahmed)

## Contribution

This project was developed by **Eng: XE Ahmed Refat**, with significant assistance from **Grok**, an AI assistant created by xAI. Grok contributed to:
- Generating 35 quiz questions (20 MCQs, 15 True/False) based on the Section 7 PowerPoint.
- Writing clean, efficient HTML, CSS, and JavaScript code.
- Ensuring technical accuracy and adherence to project requirements.
- Providing guidance on responsive design, animations, and accessibility features.

Contributions, suggestions, or improvements are welcome! Please submit issues or pull requests on the [GitHub repository](https://github.com/Xeahmed).

## License

MIT License

Copyright (c) 2025 Eng: XE Ahmed Refat

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
