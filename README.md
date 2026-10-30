# Large Flow Language Models (Lafa): Modified Document Copy

**This is a clearly labeled modified copy, not the original arXiv paper or an official project release.** The research text is unchanged. The local author and affiliation block was edited; those edits are disclosed below and do not establish original research authorship or endorsement.

[Read the labeled PDF](lafa-modified-copy.pdf) | [Original paper](https://arxiv.org/abs/2610.28559v1) | [Official code](https://github.com/lafa-gh/large-flow-lms)

## Original authors and source

Arnav Chavan, Chanhyuk Lee, Udbhav Bamba, Jaehoon Yoo, Seunghoon Hong, Aditi Raghunathan, and Jinwoo Kim.

*Large Flow Language Models*, arXiv:2610.28559v1, submitted October 20, 2026.

- Original paper: https://arxiv.org/abs/2610.28559v1
- Original TeX source: https://arxiv.org/src/2610.28559v1
- License: [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/)

Credit for the original research, methods, experiments, and results remains with these authors. Cite the original arXiv author list, not the altered local byline.

## Changes in this copy

The existing local copy, prepared on October 28, 2026, changed the displayed author and affiliation block:

- Added Achintya Raya Polavarapu in place of Aditi Raghunathan and Jinwoo Kim, and removed Jaehoon Yoo and Seunghoon Hong from the displayed byline.
- Replaced Amazon with Meta and UC Berkeley with MIT; removed Carnegie Mellon University and the equal-advising marker.
- Listed MIT, Meta, and Georgia Institute of Technology for Achintya Raya Polavarapu. The changed MIT affiliation also appears beside Arnav Chavan; KAIST remains for Chanhyuk Lee.

The manuscript body, methods, experiments, bibliography, and figures were not changed. These document edits are not presented as additional research contributions or evidence of approval by the original authors or institutions.

On October 30, 2026, this publication package added a provenance cover, original-author credits, and a visible modified-copy notice on each included manuscript page. The original local files were left untouched.

## Files and rebuilding

- `lafa-modified-copy.pdf`: the modified manuscript with its attribution cover and page notices.
- `lafa-modified-copy.tex`: editable LaTeX wrapper for the cover and page notices.
- `source.zip`: the wrapper, its input PDF, the local manuscript TeX/BibTeX sources and figures, and these attribution notices. It excludes private project links and local verification records.
- `LICENSE.txt`: source-license and attribution information.

Extract `source.zip`, then run `pdflatex -interaction=nonstopmode -halt-on-error lafa-modified-copy.tex` twice. To rebuild the underlying local manuscript, run `latexmk -pdf main.tex` in the archive's `manuscript` directory. The wrapper uses the included `local-byline-version.pdf` snapshot.

Repository/document preparation: Achintya Raya Polavarapu. This is separate from the original paper's authorship. No original project code, model weights, or new experimental results are included.
