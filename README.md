# Reed Markham's Resume

[![](https://badgen.net/github/license/thehale/expressive-resume)](https://github.com/thehale/expressive-resume/blob/master/LICENSE)

An implementation of Joseph Hale's Expressive Resume (see above), integrating GitHub Actions to automatically compile PDF copies of newly-edited files.

## Usage

Clone this repo locally.

Edit any of the `.cls` files to adjust the base themes, types, etc.

Edit either of the `.tex` files to adjust the actual resume or cover letter.

Commits to any branch that update any of these files above will generate PDFs as artifacts of the respective workflow run.

## Where can I find the resume or cover letter?

[Resume](https://github.com/reedmarkham/resume/actions/workflows/resume-to-pdf.yml)

[Cover letter](https://github.com/reedmarkham/resume/actions/workflows/cover-letter-to-pdf.yml)