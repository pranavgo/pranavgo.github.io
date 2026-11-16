# Revised research CV

This version uses a copy of the original `resume.cls` from `C:\Users\prgoyal\Pranav_Goyal_CV`, with 12-point body text and protection against stranded role headings. The original CV source, class, CV PDF, and resume PDF are unchanged.

Edit `Pranav_Goyal_CV_Research_2027.tex`. From this directory, build with:

```powershell
pdflatex -interaction=nonstopmode -halt-on-error Pranav_Goyal_CV_Research_2027.tex
```

The reviewed PDF is also saved one directory above, at `files/Pranav_Goyal_CV_Research_2027.pdf`. Update that copy after rebuilding.

The revised version retains the original font family, page margins, and section rules. Section content shares one left edge, with publication numbers and bullet markers beside it. Author lists use a consistent 11-point size with names kept intact; body text is 12-point. It uses a one-line research focus, puts publications before experience, and lets sections flow without forced page breaks or repeated continuation headings. The earlier HTML draft has been superseded by this LaTeX source.
