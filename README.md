# Student Search App 🎓

A lightweight web tool to verify student names against a database. This project demonstrates basic DOM manipulation, event handling, and conditional logic in JavaScript.

## 🔗 Live Demo
Check out the functional search tool here:  
**[https://mohammedhasarme58-lab.github.io/YOUR_REPO_NAME/](https://mohammedhasarme58-lab.github.io/YOUR_REPO_NAME/)**

---

## 🛠️ Technical Overview
The app uses a simple front-end stack (HTML5, CSS3, and Vanilla JavaScript) to perform real-time lookups.

### Features
* **Search Logic:** Uses `.includes()` to check for matches in a static array.
* **Dynamic UI:** Updates the DOM to show results in green (found) or red (not found).
* **Responsive Styling:** Clean, centered layout optimized for mobile and desktop.

### Logic Preview
```javascript
const students = ["Alice", "Bob", "Charlie"];

function searchStudent() {
    const input = document.getElementById("studentInput").value;
    // ... logic to update UI based on input
}
