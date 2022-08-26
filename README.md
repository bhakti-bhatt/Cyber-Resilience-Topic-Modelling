# Cyber-Resilience-Topic-Modelling

For a Major Research Project submitted to Toronto Metropolitan University (TMU)
## Purpose

Topic Modelling using LDA techniques on academic literature related to cyber resilience

### Abstract 

Cyber resilience is receiving increasing attention today. By definition, cyber resilience enables business continuity by preparing for, responding to, and recovering from cyber activities. The aim of this study is to investigate the themes and trends in cyber resilience research using text mining tools. We applied bibliometric analysis and Latent Dirichlet Algorithm (LDA) topic modeling on text found in 1252 academic articles from 1995 to 2022, to empirically identify key research topics and their respective trends. The findings reveal a promising interest in cyber resilience. We also extrapolate and present the topics in academic literature before and after the pandemic to draw comparisons. Thus, we present 29 topics and two high-level themes in cyber resilience research, their evolution overtime, and provide a comparison of the topics in literature pre- and post-pandemic. The results highlight research gaps in the domain which will aid researchers in making informed decisions on future studies.

## Dataset ###

#### Downloaded pdf files 

https://drive.google.com/drive/folders/19OxaCKotw0Y8vycYOdiMbQ7d8d3BqwXO

#### Scopus Article Extract & Full Text Extract from pdf files

https://drive.google.com/drive/folders/18Mt4BTjhGSBDcrSTqiVdSneXeuvEDRM7

## Description of the notebooks

#### 1 - create csv full text

extract the full-text from PDF files

#### 2 - csv full text remove references & blanks & language test

removes the reference section from the full-texts, also incorporates a step-by-step process to remove references in special cases that it needs to be done manually, non-English texts, blank documents and unreadable papers are also removed

#### 3 - data cleansing

removes email addreses, new line characters, website addresses, unnecessary text ("cid:", etc.), date formats, and numbers 

#### 4 - papers aggregation & duplicate removal & language test

the final pre-processing controls including identifying duplications, and aggregating the data with the original Scopus output

#### 5 - topic modeling all papers

the topic modeling using LDA MALLET for the full corpus, getting the dominant topics, word composition, and top representative papers for each

#### 5_1 - topic modeling post-pandemic 2021-22

the topic modeling using LDA MALLET for the 2021-22 corpus, getting the dominant topics, word composition, and top representative papers for each

#### 5_2 - topic modeling post-pandemic 2018-19

the topic modeling using LDA MALLET for the 2018-19 corpus, getting the dominant topics, word composition, and top representative papers for each

#### 6. exploratory data anlaysis

graphs and other analysis completed as part of EDA
