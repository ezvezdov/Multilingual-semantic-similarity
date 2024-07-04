My project at CTU FEE on theme
# Multilingual semantic similarity [\[PDF\]](Multilingual%20semantic%20similarity.pdf)

**Abstract**
 
In certain foreign languages, a common issue arises when individuals incorrectly write words by omitting diacritics or altering letters. This problem is prevalent in social media, chatbots, and other informal written communications. As a result, embedding models face challenges in comprehending text without diacritics (hereinafter diacriticless). A potential solution involves adapting data representation to accommodate both formal and informal styles of writing. The objective of this study is to assess the quality of diacriticless models.


## Linux dependencies for building LaTeX

```bash
sudo apt install texlive texlive-latex-extra texlive-lang-czechslovak texlive-science texlive-pstricks latexmk texmaker texlive-font-utils texlive-fonts-extra texlive-bibtex-extra biber okular pdf-presenter-console dvipng sketch
```

## Build using supplied Makefile

Build the pdf by running
```bash
make
```
in the thesis's folder.
The build is facilitated via `latexmk`.
The output will appear in the `build` subfolder.