# Parent Teacher Conference Form

A modern, responsive web form designed for scheduling and managing parent-teacher meetings. This project was developed as part of the **FreeCodeCamp (FCC)** certification, focusing on HTML5 semantic best practices, accessibility, and modern CSS styling.

## 🚀 Features

* **Modern Dark Mode Design:** Uses a sophisticated dark color palette (`MidnightBlue`) combined with translucent containers to create a clean, eye-catching UI.
* **Fully Responsive Layout:** Seamlessly adapts to both mobile devices and desktop screens using max-widths and relative units (`rem`).
* **Advanced Form Customization:** Complete styling of native browser elements to maintain a consistent aesthetic across different platforms.

---

## 🛠️ CSS Techniques & Features

The highlight of this project is the implementation of advanced selectors and pseudo-elements to maintain a clean HTML structure without unnecessary classes:

### 🌟 Pseudo-classes & Negation Selectors
* **`:not()`**: Strategically used to apply block properties to most `<label>` and `<input>` tags while excluding specific custom elements like `.contact-method` and `.contact-method-radio-btn`. This keeps the code DRY (*Don't Repeat Yourself*).
* **`:checked`**: Used to detect the active state of the custom radio buttons and trigger smooth visual transitions.
* **`:hover`**: Applied to the submit button (`.submit-btn`) to enhance user experience (UX) with an interactive, smooth color shift.

### 🌟 Pseudo-elements
* **`::placeholder`**: Customized to align the input hint text with the overall light typography (`whitesmoke`).
* **`::before`**: Used in combination with `appearance: none` to rebuild the radio button's inner indicator from scratch, adding a custom scale effect and transition animations when selected.

---

## 📁 CSS Architecture

The stylesheet follows a logical cascade structure:
1.  **Global Styles (`body`):** Main background configuration and base font colors.
2.  **Container Layout:** Centering, spacing, and smooth depth shadows (`box-shadow`).
3.  **Form Structure:** Structural styling for `fieldset`, `legend`, and block alignments.
4.  **Interactive Components:** Specific rules for text inputs, textareas, dynamic radio buttons, and the submit button.

---

## 🔧 Installation & Local Preview

To run or review this project locally:

1. Clone the repository:
```bash
   git clone [https://github.com/your-usuario/parent-teacher-conference-form-fcc.git](https://github.com/JosueVasquez22305/parent-teacher-conference-form-fcc.git)