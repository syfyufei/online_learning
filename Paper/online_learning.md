---
output:
  bookdown::pdf_document2:
    keep_tex: true
    fig_caption: true
    latex_engine: xelatex
    number_sections: true
  bookdown::word_document2:
    reference_docx: "template_CHN.docx"
    keep_md: true
    number_sections: FALSE
knit: (function(inputFile, encoding) {rmarkdown::render(inputFile, encoding = encoding, output_format = c("bookdown::word_document2", "bookdown::pdf_document2")) })
documentclass: ctexart

fontsize: 12pt
geometry: margin=1in
# bibliography: /Users/sunyufei/Desktop/Zotero.bib
csl: "/Users/sunyufei/Documents/Yufei_Sun/THU/Education/Programming/R/Zotero/styles/american-political-science-association.csl"
link-citations: true
colorlinks: true
toc: false

editor_options: 
  markdown: 
    wrap: sentence

title: '宣传式教育还是教育式宣传：授课形式对在线思政课教学效果的影响研究'
subtitle: "基于列表实验和析因实验的证据"

author:
# - 胡悦^[清华大学政治学系助理教授]
# - 孙宇飞^[清华大学政治学系博士生]

abstract: |
  
  
  **关键词:** 在线教育, 职业教育, 思政课, 教师呈现.
---



# 研究缘起

## 研究背景

## 研究问题的提出

# 文献回顾与研究假设

## 教师呈现的现有研究

## 思政课的现有研究

## 现有研究的不足

# 数据来源与实证设计

## 数据来源与变量设置

## 析因实验

## 列表实验

# 实证研究结果

# 发现与讨论
