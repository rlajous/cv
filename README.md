# Rodrigo Manuel Navarro Lajous - CV & Cover Letter Repository

This repository contains the LaTeX source files for my curriculum vitae (CV) and a customizable cover letter template. The documents are styled using consistent formatting and professional fonts and include various customization options, making them ideal for generating tailored resumes and cover letters for different job applications.

## Repository Structure

```bash
.
├── main.tex                 # Main CV LaTeX file
├── cover_letter.tex        # Cover letter template
├── config.tex              # Shared LaTeX configuration for CV and cover letter
└── README.md               # Repository instructions and description
```

### Files:

- **`main.tex`**: The LaTeX source for my CV. It contains my professional experience, education, skills, and relevant projects.
- **`cover_letter.tex`**: A reusable LaTeX cover letter template with placeholders to easily customize it for various job applications.
- **`config.tex`**: The shared LaTeX configuration file that sets the font (Times New Roman) and manages the layout for both the CV and cover letter, ensuring consistency in style across documents.

## Getting Started

To use or modify the files in this repository, you will need a LaTeX distribution. You can either:
- Use [Overleaf](https://www.overleaf.com/), an online LaTeX editor, or
- Install LaTeX locally on your machine (e.g., using **TeX Live** or **MikTeX**).

### Overleaf Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/rlajous/cv.git
    ```

2. Upload the files (`main.tex`, `cover_letter.tex`, `config.tex`) to Overleaf.
3. Customize the contents in `main.tex` or `cover_letter.tex` as needed.
4. Compile the document to generate the PDF.

### Local Setup

1. Ensure you have LaTeX installed on your system (e.g., TeX Live, MikTeX).
2. Clone the repository:
    ```bash
    git clone https://github.com/rlajous/cv.git
    ```
3. Customize the contents of `main.tex` or `cover_letter.tex` as needed.
4. Compile the LaTeX files:
    ```bash
    pdflatex main.tex      # For the CV
    pdflatex cover_letter.tex   # For the cover letter
    ```

## Customizing the Cover Letter

The `cover_letter.tex` template is designed to be flexible and reusable across multiple job applications. Here’s how you can modify it:

1. **Contact Information**: Update your contact details at the top of the letter.
2. **Job-Specific Details**: Customize the job title, company name, and any relevant details.
3. **Content Structure**: Follow the included comments to guide you through writing your cover letter's opening, middle, and closing sections.

## License

This repository is available under the MIT License. You may use, modify, and distribute its contents for personal and professional purposes.
