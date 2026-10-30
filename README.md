# Large Flow Language Models (Lafa): Modified Document Copy



[Read the labeled PDF](lafa-modified-copy.pdf) | [Original paper](https://arxiv.org/abs/2610.28559v1) | [Official code](https://github.com/lafa-gh/large-flow-lms)






- `lafa-modified-copy.pdf`: the 27-page modified manuscript with page notices and no added cover.
- `lafa-modified-copy.tex`: editable LaTeX wrapper for the page notices.
- `source.zip`: the wrapper, its input PDF, the local manuscript TeX/BibTeX sources and figures, and these attribution notices. It excludes private project links and local verification records.
- `LICENSE.txt`: source-license and attribution information.

Extract `source.zip`, then run `pdflatex -interaction=nonstopmode -halt-on-error lafa-modified-copy.tex` twice. To rebuild the underlying local manuscript, run `latexmk -pdf main.tex` in the archive's `manuscript` directory. The wrapper uses the included `local-byline-version.pdf` snapshot.

Repository/document preparation: Achintya Raya Polavarapu. This is separate from the original paper's authorship. No original project code, model weights, or new experimental results are included.
