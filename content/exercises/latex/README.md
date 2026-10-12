# LaTeX submissions

Each exercise directory contains its own `submission.tex`, which loads the shared preamble and header from `../latex/common.tex`. Set `\sheetnumber` and optionally `\submissionauthor` before loading the preamble.

Compile from the exercise directory:

```powershell
pdflatex -interaction=nonstopmode -halt-on-error submission.tex
pdflatex -interaction=nonstopmode -halt-on-error submission.tex
```

The output is `submission.pdf` alongside the source. Inspect the PDF after making changes. Keep transcription corrections and missing handwritten material in a separate `TRANSCRIPTION.md` file.
