---
title: Título de vuestro proyecto
author: 
- autor 1
- autor 2
- autor 3
papersize: a4paper
geometry: margin=4cm
fontsize: 11pt
bibliography: recursos/referencias.bib 
csl: recursos/chicago-author-date-es.csl
lang: es
toc: true
header-includes:
    - \usepackage{MinionPro}
    - \usepackage[hang,flushmargin]{footmisc}
    - \usepackage{fancyhdr}
    - \usepackage[yyyymmdd,hhmmss]{datetime}
    - \pagestyle{fancy}
    - \fancyhead[ER,OL]{v.\today-\currenttime}
    - \fancyhead[EL,OR]{Título de vuestro proyecto}
    - \fancyfoot[EC,OC]{\thepage}
...
