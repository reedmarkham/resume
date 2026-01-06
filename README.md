# Reed Markham's Resume (and Cover Letter)

[![Resume CI/CD](https://github.com/reedmarkham/resume/actions/workflows/resume-to-pdf.yml/badge.svg)](https://github.com/reedmarkham/resume/actions/workflows/resume-to-pdf.yml)
[![Cover Letter CI/CD](https://github.com/reedmarkham/resume/actions/workflows/cover-letter-to-pdf.yml/badge.svg)](https://github.com/reedmarkham/resume/actions/workflows/cover-letter-to-pdf.yml)

This project combines Joseph Hale's [Expressive Resume](https://github.com/thehale/expressive-resume/tree/main), Xu Cheng's [LaTeX Action](https://github.com/xu-cheng/latex-action), and Eloy López's [poppler-utils](https://github.com/elswork/poppler-utils) to deploy a LaTeX-generated resume and cover letter as PDF files using GitHub Actions.

## Usage

* Clone this repo locally.
* Edit any of the `.cls` files to modify the LaTeX classes used in the resume and/or cover letter.
* Edit either of the `.tex` files to write the actual resume or cover letter.
* Commit to any branch, updating any of these files above, to generate PDFs as artifacts of the respective workflow run.
* The GitHub Actions fails out if the resume is detected to be generated in a length exceeding 1 PDF page.
