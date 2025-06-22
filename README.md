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

## Installation
```bash
git clone https://github.com/your-username/student_grading_system.git
cd student_grading_system
cargo build

How to Run
Execute the program with:

bash
cargo run


Example Usage
Program output will look like:

text
=== Student Grade System ===
Enter student name: John Doe
Enter total marks: 285
Enter number of subjects: 4

Report Card:
-----------------
Name: John Doe
Marks: 285
Subjects: 4
Average: 71.25%
Grade: C
-----------------
PDF generated: report_card.pdf
File Structure
text
student_grading_system/
├── src/
│   └── main.rs
├── Cargo.toml
└── report_card.pdf

## Running the Program
```bash
cargo run

## 
