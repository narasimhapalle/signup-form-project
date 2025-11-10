# signup-form-project
“A simple and interactive Sign-Up Form built using HTML &amp; CSS. Includes field validation, hover hints, and real-time email check indicators.”
# 🧾 Sign-Up Form Project
---
## 🌟 Features
✅ Uses HTML5 form elements like:
- `<form>` – to collect user input  
- `<input>` – for text, email, password, radio, number fields  
- `<label>` – to describe each input field  
- `<table>` – to align input fields neatly  
- `<p>` – to display hints on hover  
- `<img>` – to show validation icons (✅ / ❌)  

✅ CSS properties used:
- Pseudo-classes like `:required`, `:optional`, `:focus`, `:valid`, `:invalid`, `:hover`
- Border styles (`groove`, `dashed`, `dotted`)
- Display and visibility control using `display: none` and `display: inline`
- Read-only and disabled input field styling

---

## 💻 Technologies Used
- **HTML5** — For structure and form elements  
- **CSS3** — For styling, interactivity, and validation feedback  

---

## 🧠 HTML Elements Explanation

| Element | Purpose |
|----------|----------|
| `<form>` | Defines the sign-up form |
| `<table>` | Arranges labels and input boxes properly |
| `<label>` | Adds text description for inputs |
| `<input type="text">` | Takes name and other text input |
| `<input type="email">` | Validates email automatically |
| `<input type="password">` | Hides password characters |
| `<input type="radio">` | Lets users choose gender |
| `<input type="number">` | Accepts numeric input like age |
| `<input type="submit">` | Submits the form |
| `<p>` | Displays hints or messages when hovered |
| `<img>` | Shows tick and cross icons for validation |

---

## 🎨 CSS Highlights
- **`input:focus`** → highlights the active field  
- **`input:hover + p`** → shows helpful text when hovered  
- **`input[type="email"]:valid` / `:invalid`** → toggles success/error icons  
- **`input:read-only`** → makes a field non-editable  
- **`input:disabled`** → grays out fields that cannot be changed  

---

## 📸 Preview
> ![Form Preview](tick.png)  
> *(This is just a sample icon used in validation feedback)*

---

## 🚀 How to Run
1. Clone or download the repository  
2. Make sure all files (`index.html`, `index10.css`, `tick.png`, `chek.png`) are in the same folder  
3. Open **index.html** in your browser  
4. Type valid/invalid email → watch icons appear ✅❌  

---

## 💬 Author
👤 **Palle Narasimha**  
💻 Front-End Developer | Java Full Stack Enthusiast  

---

## 🌐 Live Demo
🔗 [View on GitHub Pages](https://yourusername.github.io/signup-form-project/)
