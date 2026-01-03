# Musa Sahin - Interactive Developer CV

This is a personal CV/Resume website built with HTML, CSS, and JavaScript. It features a modern, responsive design and a **high-fidelity native PDF generation** capability.

## Features

- **Responsive Design:** Optimized for desktop, tablet, and mobile viewing.
- **Premium UI:** Custom styled header, clean typography (Inter font), and categorized skills section.
- **Native PDF Generation:** A "Download PDF" button that leverages the browser's native print engine (`window.print()`) with dynamic CSS injection. This ensures:
  - **Vector Quality:** Text is selectable and crystal clear.
  - **Single Page Layout:** Automatically calculates content height to prevent awkward page breaks.
  - **Optimized Print Styles:** Removes shadows and adjusts colors specifically for print/PDF export.
- **Dynamic Filename:** Automatically renames the document title to include the current date (e.g., `Musa_Sahin_CV_YYYY-MM-DD`) during the print dialog.
- **ATS Friendly:** Semantic HTML structure.
- **Favicon:** Custom tab icon included.

## Structure

- `index.html`: Main content, layout structure, and the **dynamic PDF generation logic** (embedded JavaScript).
- `style.css`: All styling, including the custom "Header Centered" premium theme and detailed `@media print` rules.
- `favicon.png`: Browser tab icon.

## How to Edit

1. **Content:** Open `index.html` to update your personal information, experience, or education.
2. **Styles:** Edit `style.css` to change colors, fonts, or spacing.
3. **PDF Logic:** The PDF generation logic is located at the bottom of `index.html`. It dynamically creates a `<style>` tag to match the print paper size to the content's exact dimensions.

## 🚀 Deployment (GitHub Pages)

To publish at [https://musahinist.github.io](https://musahinist.github.io):

1.  **Repository Name:** Create a new repository named **`musahinist.github.io`**.
2.  **Push Code:**
    ```bash
    git init
    git add .
    git commit -m "Initial commit"
    git branch -M main
    # Remote URL for your user repository
    git remote add origin https://github.com/musahinist/musahinist.github.io.git
    git push -u origin main
    ```
3.  **Activate Pages:**
    - Go to Repository **Settings** > **Pages**.
    - Select Source: **Deploy from a branch** (Branch: `main`, Folder: `/`).
    - Save.

🎉 Your CV will be live at: [https://musahinist.github.io](https://musahinist.github.io)
