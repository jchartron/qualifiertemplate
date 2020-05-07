# nihf31
Format for written qualifier


You'll need to install TinyTex, Rmarkdown and Bookdown. 
If you already have LaTex installed you won't need TinyTex, but you'll need the packages in preamble.tex


In an R session:

```
install.packages(c("tinytex","rmarkdown","bookdown"))
tinytex::install_tinytex()
```

Open f31.Rmd in Rstudio, and click "knit." Tinytex should install all required latex packages.