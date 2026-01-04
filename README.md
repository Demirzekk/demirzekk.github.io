# Zekai Demir - Interactive CV Website

This is a professional CV/Resume website for **Zekai Demir**, a Senior Flutter Developer. It features a modern, responsive design, multi-language support (Turkish/English), and high-fidelity native PDF generation.

## 🌟 Features

-   **Multi-language Support (TR/EN):** Seamlessly switch between Turkish and English with a single click. State is managed via vanilla JavaScript.
-   **Responsive Design:** Fully optimized for desktop, tablet, and mobile viewing.
-   **Premium UI:** Custom styled header with glassmorphism effects, clean typography (Inter font), and modern skill tags.
-   **Native PDF Generation:** A smart "Download PDF" button that:
    -   Hides interactive elements (buttons, toggles) automatically.
    -   Optimizes colors for print (Black/White text, removal of gradients).
    -   Prevents awkward page breaks in the middle of content blocks.
    -   Generates a clean, ATS-friendly document.
-   **SEO Optimized:** Includes JSON-LD (Person & WebPage Schema) for better search engine visibility and LLM understanding.
-   **ATS Friendly:** Semantic HTML structure ensures Applicant Tracking Systems can parse the content effectively.

## 🛠 Tech Stack

-   **HTML5:** Semantic markup.
-   **CSS3:** Custom properties (variables), Flexbox/Grid, and `@media print` modifications.
-   **JavaScript:** Vanilla JS for language switching and DOM manipulation.
-   **Icons:** Font Awesome 6.

## 📂 Project Structure

-   `index.html`: Main content containing all translations and logic.
-   `style.css`: All styling, including the custom "Blue Theme" and specific `@media print` rules.
-   `README.md`: Project documentation.

## 🚀 Deployment (GitHub Pages)

This project is configured to be deployed on GitHub Pages.

**Live URL:** [https://demirzekk.github.io](https://demirzekk.github.io)

### Deployment Steps:

1.  **Repository Name:** The repository is named `Demirzekk.github.io`.
2.  **Push Code:**
    ```bash
    git init
    git add .
    git commit -m "Initial commit"
    git branch -M main
    git remote add origin https://github.com/Demirzekk/Demirzekk.github.io.git
    git push -u origin main
    ```
3.  **Settings:** GitHub Pages is enabled from the repository settings, serving from the `main` branch.

## 📝 How to Edit

1.  **Content (Text & Translations):**
    -   Open `index.html`.
    -   The `translations` object in the `<script>` tag at the bottom contains all text for both English (`en`) and Turkish (`tr`).
    -   Edit the values in this JSON object to update the CV content.
2.  **Styles:** Edit `style.css` to change colors, fonts, or spacing.
3.  **PDF Layout:** Modify the `@media print` block in `style.css` to adjust paper margins or hide specific elements.
