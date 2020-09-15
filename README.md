# apachecon-atc-api-presentation
The source for the presentation slides for the Apachecon 2020 ATC API
Presentation.

## How to build
Actually building the presentation PDF is pretty simple, just use `pdflatex`.
However, code blocks use [the minted package](https://www.ctan.org/pkg/minted)
for syntax highlight, which means that in addition to TeXLive you'll also need
Python (3 only pls) with a working `pip` and you'll need to install
[`pygments`](https://pypi.org/project/Pygments/) - generally that can be done
with just `pip install --user pygments`.
