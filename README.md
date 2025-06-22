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

### Installation
git clone https://github.com/your-username/student_grading_system.git
cd student_grading_system
cargo build

### Running the Program
bash
cargo run

✅ PDF report generated: 'report_card.pdf'
Create another report? (y/n): n
📂 Sample PDF Output
![Report Card Example](images/report_card.png)


🛠️ Dependencies
printpdf - PDF generation

Standard I/O - User input handling

🏗️ Project Structure
text
src/
├── main.rs          # Core application logic
Cargo.toml           # Dependency configuration
report_card.pdf      # Generated output


