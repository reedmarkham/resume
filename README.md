# Reed Markham's Resume (and Cover Letter)

Combining Joseph Hale's [Expressive Resume](https://github.com/thehale/expressive-resume/tree/main) and Xu Cheng's [LaTeX Action](https://github.com/xu-cheng/latex-action) to deploy a LaTeX-generated resume and cover letter as PDF files using GitHub Actions.

It will also use [poppler-utils](https://github.com/elswork/poppler-utils) bash library to confirm that the resumes are no longer than 1 page in length.

## Usage

* Clone this repo locally.
* Edit any of the `.cls` files to modify the LaTeX classes used in the resume and/or cover letter.
* Edit either of the `.tex` files to write the actual resume or cover letter.
* Commit to any branch, updating any of these files above, to generate PDFs as artifacts of the respective workflow run (see below).

## Where can I find the resume or cover letter?

[Resume](https://github.com/reedmarkham/resume/actions/workflows/resume-to-pdf.yml)

[Cover letter](https://github.com/reedmarkham/resume/actions/workflows/cover-letter-to-pdf.yml)

These artifacts will be deleted by GitHub after 90 days.
