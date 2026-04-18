# Project Documentation: Personal Portfolio Website

## Table of Contents
1. Introduction
2. Project Goals and Scope
3. Project Planning and Feasibility Study
4. Requirements Analysis and Design
5. Wireframe Design
6. Implementation and Development
7. Testing and Quality Assurance
8. Project Conclusion and Reflection

---

This documentation outlines the design, implementation, and evaluation of a Personal Portfolio Website created as a Grade 11 CS Final Project. The website serves as a digital resume for a +2 Management student to showcase skills, academic foundation, and leadership experience.

## 2. Project Goals and Scope
**Goal:** Create a 4 page responsive website exhibiting personal info, skills, hobbies, and a way to contact.
**Scope:** Includes writing clean HTML & CSS from scratch without frameworks (no Tailwind/Bootstrap permitted per rules). The website employs a coherent thematic approach denoted as "Atmospheric Precision," ensuring accessibility and a premium feel.

## 3. Project Planning and Feasibility Study
- **Timeline Strategy:** A 4 phase Gantt chart approach was utilised. (Phase 1: Planning, Phase 2: Design, Phase 3: Coding, Phase 4: Testing & Deployment).
- **Feasibility:** As an HTML/CSS vanilla project, the requirements were well within the technical boundaries and hardware limits of standard web development software (VSCode). There were no cost implications since open source fonts and tools were utilised.

## 4. Requirements Analysis and Design
- **Functional Requirements:** Navigation between 4 core pages, functional visual contact form (client side only required), and dynamic responsive layout grids.
- **Non Functional Requirements:** Fast page loading, distinct use of inline, internal, and external CSS. Color palettes translated from Tailwind configs to raw CSS variables (`#0846ed` primary).

## 5. Wireframe Design
*(Insert Wireframes & Screenshots)*
- **About Page:** Hero layout with right aligned image. Followed by a bento style skills and facts grid.
- **Skills Page:** 2 column grid representing skill bars for distinct technological competencies.
- **Hobbies Page:** 3 column photo driven grid displaying hobbies.
- **Contact Page:** Centered form with wide input layers and a prominent submit mechanism.

## 6. Implementation and Development
Four distinct `.html` pages and four `.css` layout files alongside a global `styles.css`.
- Employed `flex` and `grid` systems to establish responsive structure.
- Adhered strictly to using vanilla, framework less setup while mirroring the initial "Tailwind" theme's aesthetic choices cleanly.

## 7. Testing and Quality Assurance
Three fundamental test cases were employed:
- **Test Case 1: Navigation Links Evaluation**
  - *Action:* Click all links across top navigation and footer.
  - *Expected:* Link correctly directs user to `index.html`, `skills.html`, `hobbies.html`, `contact.html` respectively.
  - *Result:* Passed.

- **Test Case 2: Contact Form Validation**
  - *Action:* Attempt to submit contact form with empty fields.
  - *Expected:* Client side browser validation must block submission emphasizing "required" field tags.
  - *Result:* Passed.

- **Test Case 3: CSS Implementation Checks**
  - *Action:* Inspect source files for the mandatory use of inline (`style=""`), internal (`<style>`), and external (`<link rel>`) CSS.
  - *Expected:* Valid usage across all pages.
  - *Result:* Passed. Inline CSS controls specific min height properties and background width ratios. Internal CSS controls gradients and localized variables.

## 8. Project Conclusion and Reflection
This portfolio website allowed me to profoundly cement the core foundations of web architecture via HTML5 and Vanilla CSS3. Moving away from utility frameworks forced a methodical approach to grid systems and flex models, fostering a rigorous discipline toward class organization. The final output matches the requested "atmospheric" aesthetic strictly using standardized coding practices, offering a premium and fast experience ready for future hosting integration (e.g., AWS or GitHub Pages). I've focused on low level languages like C and C++ to demonstrate technical depth.
