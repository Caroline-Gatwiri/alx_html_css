# Smile School – CSS Project

This project is a continuation of the **HTML Advanced** project.  
In the previous stage, the focus was on building the correct **HTML semantic structure** of the page.  

In this stage, the goal is to bring the page to life using **CSS styling** while following the provided Figma design file.  
You will apply your CSS knowledge to style the website layout, typography, colors, and responsive behavior.

---

## 📖 Project Description

The project is a static educational website called **Smile School**.  
It highlights:
- A hero section with a call to action.
- Instructor profiles.
- Popular tutorials.
- Membership benefits.
- Testimonials.
- A Frequently Asked Questions (FAQ) section.
- A footer with branding and social media links.

The task is to use **only HTML and CSS** (no frameworks or external libraries like Bootstrap, React, or Vue) to style the page.  
This ensures you understand core CSS concepts, selectors, and the browser rendering process.

---

## 🎯 Learning Objectives

By the end of this project, you should be able to explain (without relying on Google):

1. **What is CSS**  
   - CSS (Cascading Style Sheets) defines how HTML elements are displayed.  
   - It separates content (HTML) from presentation (design).

2. **How to add style to an element**  
   - Using inline styles (`<h1 style="color:red;">`),  
   - Internal styles (`<style>` tag inside HTML), or  
   - External stylesheets (`style.css` linked with `<link>`).

3. **What is a class**  
   - A reusable CSS selector defined with a dot (`.classname`).  
   - Example: `.btn { background-color: blue; }`.

4. **What is a selector**  
   - A pattern used to target and style HTML elements.  
   - Examples:  
     - `p` → all `<p>` tags.  
     - `.title` → elements with class `title`.  
     - `#main` → element with ID `main`.  
     - `div > p` → `<p>` directly inside a `<div>`.

5. **How to compute CSS Specificity Value**  
   - Specificity determines which style takes priority when multiple rules apply.  
   - Order of importance:  
     - Inline styles → highest (`1000`).  
     - IDs → `100`.  
     - Classes, attributes, pseudo-classes → `10`.  
     - Elements, pseudo-elements → `1`.

6. **What are Box properties in CSS**  
   - Every element in CSS is treated as a **box**.  
   - Box model includes:  
     - `content` (text, image, etc.),  
     - `padding`,  
     - `border`,  
     - `margin`.

7. **How does the browser load a webpage**  
   - Browser requests the HTML file from the server.  
   - Parses the HTML and builds the DOM (Document Object Model).  
   - Loads CSS and builds the CSSOM (CSS Object Model).  
   - Combines DOM + CSSOM into the **Render Tree**.  
   - Calculates layout and paints pixels on the screen.

---

## 📌 Requirements

- All project files must end with a **new line**.  
- A **README.md** file is mandatory at the root of the project folder.  
- You are **not allowed to use external libraries or frameworks** (e.g., Bootstrap, React, Vue, NodeJS).  
- The project must be built using **only HTML, CSS, and JavaScript**.  
- Code must be **W3C compliant** and validate with the [W3C Markup Validator](https://validator.w3.org/).  
- All images must be properly added to the `images/` folder and referenced in the HTML.  
- Final design should match the provided **Figma file**.

---

## 🛠 Project Setup

1. Clone or download this repository.  
2. Open the project folder in your code editor (VS Code recommended).  
3. Open `index.html` in a browser to view the page.  
4. Apply styles in `style.css` and link it inside `index.html`:
   ```html
   <link rel="stylesheet" href="style.css">
