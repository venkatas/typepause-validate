# typepause-validate

**typepause-validate** is a user-friendly form validation proof-of-concept that improves the user experience by delaying validation messages until the user pauses typing. It adapts to typing speed and prevents premature or intrusive error messages. Built with pure HTML and JavaScript — no dependencies required.

## 🌟 Features

- ✅ Smart, debounced validation based on user typing speed
- ⏳ Delays validation until the user pauses input
- 🛑 Prevents error messages while typing or switching tabs
- 📄 Validates Email, Credit Card, Aadhaar, and Mobile Number fields
- ⚡ Lightweight and dependency-free

## 🚀 Getting Started

### Prerequisites
Just a modern web browser — no frameworks or libraries required.

### Running the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/typepause-validate.git

2. Open the HTML file in your browser:
  ```bash
  cd typepause-validate
  open index.html  # or double-click the file

That’s it! You’ll see a form that waits for user input to pause before showing validation messages.

🧠 Use Case
Traditional form validation often interrupts the user experience by showing error messages mid-typing. This POC introduces a friendlier UX — only triggering validations when the user has stopped typing for a moment, improving both accessibility and interaction comfort.

🧪 Fields Covered
Email Address – Must follow standard email format.
Credit Card Number – Must be 16 digits.
Aadhaar Number – Must be 12 digits (Indian national ID).
Mobile Number – Must be 10 digits, starting with 6-9.
