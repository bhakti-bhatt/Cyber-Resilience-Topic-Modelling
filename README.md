# Cyber-Resilience-Topic-Modelling
For a Major Research Project submitted to Toronto Metropolitan University (TMU)
### Purpose: Topic Modelling using LDA techniques on academic literature related to cyber resilience

Dataset Used:
To be updated with link

Description of the notebooks:

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
