# 📚 Student Grading System in Rust

A console application that generates student report cards with grade calculation and PDF export functionality.

![Rust](https://img.shields.io/badge/Rust-1.70+-orange?logo=rust)
![License](https://img.shields.io/badge/License-MIT-blue)

## ✨ Features

- 📝 Input student details (name, total marks, subjects)
- 🧮 Automatic average calculation
- 📊 Grade assignment (A/B/C/D)
- 🖨️ Console report card display
- 📄 PDF report generation (with `printpdf` crate)
- ♻️ Interactive loop for multiple entries

## 🚀 Getting Started

### Prerequisites
- Rust 1.70+ ([install](https://www.rust-lang.org/tools/install))
- `printpdf` dependencies:
  ```bash
  # Ubuntu/Debian
  sudo apt install libfreetype6-dev
  
  # macOS (Homebrew)
  brew install freetype

Installation
bash
git clone https://github.com/your-username/student_grading_system.git
cd student_grading_system
cargo build
Execution
bash
cargo run
🖥️ Usage
Example Session
text
=== Student Grade System ===
Enter student name: Alice Johnson
Enter total marks: 345
Enter number of subjects: 4

Report Card
----------------------------
Student Name: Alice Johnson
Total Marks: 345
Number of Subjects: 4
Average: 86.25%
Grade: B
----------------------------

✅ PDF report generated: 'report_card.pdf'
Create another report? (y/n): n
Output Files
https://images/report_card.png

⚙️ Technical Details
Dependencies
printpdf - PDF generation

Standard I/O - User input handling

Project Layout
text
src/
├── main.rs          # Core application logic
Cargo.toml           # Dependency configuration
report_card.pdf      # Generated output
🤝 Contributing
Fork the project

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some amazing feature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

📜 License
Distributed under the MIT License. See LICENSE for more information.

🦀 Made with Rust | 💖 Happy Coding!
