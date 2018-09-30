This is a template thesis of RUC(Republic University of China). Thanks to the **bookdown**(https://github.com/rstudio/bookdown), now you can write your thesis using the Rmarkdown syntax.

# Usage

## Latex Environment
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

## Thesis 

Set the basic infomation in the `index.Rmd` file.

```yaml
title: "论贸易战对中国未来经济的影响"
author: "yimeng"    
date: "`r Sys.Date()`"
# 文档类型，不同学位的论文要设置不同的 key
# 本科: document-bachelor: true
# 专硕: document-premaster: true
# 硕士: document-master: true
# 博士: document-doctor: true
document-bachelor: true
abstract-zh: "中文摘要: RUCThesis 是根据中国人民大学《本科论文指导手册》和《研究生学位论文及其摘要的撰写和印制要求》而制作的 \\LaTeX\\ 论文模板。"
abstract-en: "This is a English abstract."
baseinfo:
  subtitle: "基于统计模拟的经济学预测方法"  # 论文副标题
  studentid: "20163160102"                  # 学号
  school: "统计学院"                        # 学院
  field: "经济统计学"                       # 专业
  advisor: "yalei"                          # 导师
  grade: "2016级"                           # 年级 
  thesiscode: "RUC-BK-050101-2014201237"    # 论文编码RUC-BK-专业代码-学号
  score: "4.0"                              # 论文成绩，可不填
  date: "`r Sys.Date()`"                    # 日期
  keywordzh: ["贸易战", "经济"]             # 中文摘要关键词
  keyworden: ["Trade War", "Economics"]     # 英文摘要关键词
masterinfo:  # 设置英文标题和主题词, 本科生不需要填写
  etitle: "LaTeX template of Renmin university of China"
  keywords: "Keywords 论文主题词"
```

# Fonts
You need to install `SimSun`, `SimHei`, `FangSong` fonts if you are you not using the Windows system. You can download them from [StellarCN/scp_zh](https://github.com/StellarCN/scp_zh/tree/master/fonts), I do not encourage you to do it.

The latex files in the project are copied  from [GH1995/RUC-thesis-template-for-LaTeX](https://github.com/GH1995/RUC-thesis-template-for-LaTeX). 


