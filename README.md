# Security Testing — Course Notes
This repository contains unofficial notes for the course **Security Testing**, held by **Professor Alessandro Marchetto** at the University of Trento, Master's Degree in Computer Science.

[View Notes (PDF)](notes.pdf)

The notes have been created based on the lecture slides and additional reference materials, with the goal of supporting students in their study and providing a clear, structured overview of the topics covered in the course.

> **Disclaimer**  
> These notes are **not official material** and should not be considered a replacement for the lectures or official resources provided by the instructor.

---

## About the Notes

- The notes aim to:
  - Organize the course content in a **clear and structured** manner
  - Cover the main theoretical concepts discussed during the lectures
  - Serve as a **study aid** and reference document
- While care has been taken to ensure correctness, the wide range of topics may result in **mistakes or inaccuracies**.

---

## Repository Structure

- The repository contains the **LaTeX source code** used to generate the notes
- You are free to:
  - Clone the repository
  - Modify or extend the notes
  - Build the PDF locally

---

## Requirements

To compile the notes locally you will need:

- A recent **LaTeX distribution**, for example:
  - **TeX Live** (Linux/macOS)
  - **MacTeX** (macOS)
  - **MiKTeX** (Windows)

Optional but recommended for development:

- **Visual Studio Code**
- **LaTeX Workshop** extension for VS Code
---

## How to Build the PDF Locally

1. **Clone the repository**

   ```bash
   git clone https://github.com/446f6e6e79/Security-Testing-Notes
   cd Security-Testing-Notes
   ```

2. **Open the project in VS Code**

   ```bash
   code .
   ```

3. **Install and configure LaTeX Workshop (one‑time)**

   - Install the **LaTeX Workshop** extension in VS Code  
   - Make sure your LaTeX distribution (e.g. MacTeX on macOS) is installed and available in your `PATH`  
   - In VS Code settings, enable **build on save** (LaTeX Workshop will automatically compile when you save a `.tex` file)

4. **Compile the notes**

   - Open the main `.tex` file (the one that includes the others)
   - Press **Control + S** (save)  
   - LaTeX Workshop will automatically start the compilation and generate the PDF

---

## Contributing

Contributions are always very welcome!

If you find:
- Errors or inaccuracies
- Typos or unclear explanations
- Missing topics or improvements

please feel free to:
- Open an **issue**
- Submit a **pull request**

Every contribution will be taken into consideration and is highly appreciated.

---

### Contribution Workflow

To keep the repository clean and make it easy to review changes, please follow this workflow:

1. **Fork** the repository on GitHub.
2. **Clone** your fork:

   ```bash
   git clone https://github.com/446f6e6e79/Security-Testing-Notes
   cd Security-Testing-Notes
   ```

3. **Create a feature branch**:

   ```bash
   git checkout -b feature/my-change
   ```

4. **Make your changes** in the `.tex` files:
   - Keep the existing structure and style where possible.
   - Save the file (**⌘S**) and let LaTeX Workshop recompile to ensure it builds without errors or warnings.

5. **Compile and check the PDF**:
   - Verify that the PDF builds correctly.
   - Check for layout issues (overfull boxes, broken references, etc.).

6. **Commit** your changes with a clear message:

   ```bash
   git add .
   git commit -m "Fix typos in section on X"   # example
   ```

7. **Push** your branch and open a **Pull Request** from your fork to the main repository:
   - Describe briefly what you changed.
   - Mention any remaining doubts or things that should be double-checked.

--- 

### Reporting Issues

If you prefer not to modify the LaTeX yourself, you can still help:

- Open an issue describing:
  - The **section** and **page** (if possible) where the problem is.
  - A short description of the error or missing explanation.
  - (Optional) A suggested correction or additional reference.

This feedback is very useful to improve the notes for everyone.
