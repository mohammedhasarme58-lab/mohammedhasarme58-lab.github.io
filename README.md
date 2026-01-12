# Student Search App 🎓

A lightweight web tool to verify student names against a database. This project demonstrates basic DOM manipulation, event handling, and conditional logic in JavaScript.

## 🔗 Live Demo
Check out the functional search tool here:  
**[https://mohammedhasarme58-lab.github.io/](https://mohammedhasarme58-lab.github.io/)**

---

## 🛠️ Project Structure
The app uses a single-file architecture (HTML5, CSS3, and Vanilla JavaScript) to perform real-time lookups.

### Search Logic
The app compares user input against a predefined list using the `.includes()` method:

```javascript
const students = ["Alice", "Bob", "Charlie"];

function searchStudent() {
    const input = document.getElementById("studentInput").value;
    const resultDiv = document.getElementById("result");

    if (students.includes(input)) {
        resultDiv.textContent = `✓ "${input}" is in the student list!`;
        resultDiv.style.color = "green";
    } else {
        resultDiv.textContent = `✗ "${input}" is NOT in the student list!`;
        resultDiv.style.color = "red";
    }
}
