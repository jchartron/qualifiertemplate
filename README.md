# nihf31
Format for written qualifier

## Installation

You'll need to install TinyTex, Rmarkdown and Bookdown. 
If you already have LaTex installed you won't need TinyTex, but you'll need the packages in preamble.tex


In an R session:

```
install.packages(c("tinytex","rmarkdown","bookdown"))
tinytex::install_tinytex()
```

Open f31.Rmd in Rstudio, and click "knit." Tinytex should install all required latex packages.

## Editing
Most formatting is provided in the preamble.tex file.
In particular, you can change spacing in the block:

```
\usepackage{titlesec}
\titlespacing*{\section}{0pt}{6pt plus 4pt minus 2pt}{0pt plus 2pt minus 2pt}
\titlespacing*{\subsection}{0pt}{6pt plus 4pt minus 2pt}{0pt plus 2pt minus 2pt}
\titlespacing*{\subsubsection}{0pt}{2pt plus 4pt minus 2pt}{0pt plus 2pt minus 2pt}
\titlespacing*{\paragraph}{0pt}{0pt plus 4pt minus 2pt}{6pt plus 1pt minus 1pt}
\titlespacing*{\subparagraph}{0pt}{0pt plus 4pt minus 2pt}{6pt plus 1pt minus 1pt}
```

