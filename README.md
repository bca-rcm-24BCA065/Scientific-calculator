🧠 Features to Include
Basic Operations
Addition (+)

Subtraction (−)

Multiplication (×)

Division (÷)

Modulus (%)

Advanced Operations
Exponentiation (xʸ, x²)

Square root (√x)

Cube root (∛x)

Logarithmic functions (log, ln)

Trigonometric functions: sin, cos, tan, and their inverses

Factorial (n!)

Power of 10 (10^x)

Reciprocal (1/x)

Constants: π (Pi), e (Euler’s Number)

Memory functions: M+, M−, MR, MC (optional)

📄 File Structure
bash
Copy
Edit
/scientific-calculator/
│
├── index.html         # Layout structure
├── style.css          # Styling
└── script.js          # Functionality
🖼 HTML Layout
Use a <table> or <div>-grid layout for buttons.

Include:

Display screen (<input type="text" id="display">)

Buttons grouped by categories (basic, scientific)

🎨 CSS Styling
Make it clean and responsive.

Use grid or flexbox for layout.

Style buttons with hover and click effects.

Dark/light mode toggle (optional)

⚙ JavaScript Functionality
1. Event Handling
Capture button clicks using addEventListener.

2. Parsing Expressions
Use Math functions (Math.sin(), Math.log(), etc.)

Handle degrees vs radians (use a toggle)

Optional: Build a custom parser for complex input (or use eval cautiously with sanitization)

3. Display Update
Append values to the screen as the user clicks.

Show results on pressing =

🧪 Testing & Validation
Check for:

Division by zero

Invalid input (e.g. √-4)

Edge cases (0!, log(0), etc.)

📝 README.md Suggestions (for GitHub)
Include:

Project description

Features list

How to run locally

Screenshots (optional)

Technologies used

Future improvements# Scientific-calculator
