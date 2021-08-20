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

header-includes:
   - \usepackage{makecell}
   
fontsize: 12pt
geometry: margin=1in
bibliography: online_learning.bib
csl: "china-national-standard-gb-t-7714-2015-author-date.csl"
link-citations: true
colorlinks: true
toc: false
indent: true
always_allow_html: true

editor_options: 
  markdown: 
    wrap: sentence

title: '教育式宣传与宣传式教育：政治宣传效果的整合性框架'
subtitle: "基于思政课教学的实验研究"

author:
- 孙宇飞^[清华大学政治学系博士生，联系电话：18638750921，邮箱：sunyf20@mails.tsinghua.edu.cn]
- 汤霓^[教育部职业技术教育中心研究所助理研究员，联系电话：15001918603，邮箱：tangni510@163.com]

abstract: |
  政治宣传是政府维持统治合法性和提升公众支持的重要手段之一，现有研究从“灌输机制”和“信号机制”解释政治宣传对公众态度和行为的影响，但少有研究探究两个机制之间的联系。思想政治教育课程是中国政治宣传的重要方式，是落实立德树人根本任务的关键，如何讲好思政课是一个亟待解决的时代命题。本文使用在中国开展在线调查实验获得的独特数据集，结合析因实验设计和回归分析检验了灌输理论的说服机制和信号理论的能力感知之间的关系。笔者发现，以思政课为代表的“硬宣传”在传递威慑信号之外，还具有一种说服的“软效应”。即它不仅能够使公众感受到国家维护社会稳定的强大能力，从而降低自己的抗争意愿；还能够使公众感受到国家拥有提供公共服务和促进国家认同的软实力，从而通过说服机制，增强对国家的支持。笔者提出了一个具有整合性的政治宣传影响框架。在此基础上，笔者基于内容和形式两个视角，从认同增强、能力感知和思政课喜好三个维度探索了影响思政课宣传效果的因素。笔者发现，和学生专业实践相结合的课程内容能够显著的提升受试学生的思想政治课宣传效果，但宣传内容和思政课的教师呈现方式对不同维度的国家能力感知没有显著的影响，即近年来国家倡导的“课程思政”这一“宣传式教育”的教学效果要好于传统的“教育式宣传”类型的“思政课程”。
  
  **关键词**：政治宣传；析因实验；信号机制；国家能力。
---

