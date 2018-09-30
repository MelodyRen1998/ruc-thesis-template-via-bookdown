This is a template thesis of RUC(Republic University of China). Thanks to the **bookdown**(https://github.com/rstudio/bookdown), now you can write your thesis using the Rmarkdown syntax.

# Usage

If you do not have Latex installed, I highly recommend you to use the `tinytex` package.
```r
install.packages('tinytex')
tinytex::install_tinytex()
```

When using this template, you probabily missing some latex packages. `tinytex` will try to install them automatically. However, there are two packages that tinytex can not find. Here are the commands to install them manually: 
```
system2('tlmgr install simplekv')
system2('tlmgr install pgf')
```

## Fonts
You need to install `SimSun`, `SimHei`, `FangSong` fonts if you are you not using the Windows system. You can download them from [StellarCN/scp_zh](https://github.com/StellarCN/scp_zh/tree/master/fonts), I do not encourage you to do it.

The latex files in the project are copied  from [GH1995/RUC-thesis-template-for-LaTeX](https://github.com/GH1995/RUC-thesis-template-for-LaTeX). 


