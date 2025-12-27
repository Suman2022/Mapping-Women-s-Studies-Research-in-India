# Mapping-Women-s-Studies-Research-in-India
A Topic Modeling Analysis of Doctoral Theses (2011–2020) including validation wit NCW dataset and manual analysis
📌 Overview

This repository contains code and documentation for a computational analysis of Women’s Studies doctoral theses in India, using topic modeling (LDA) and manual qualitative validation. The project examines how women-centric research themes vary across regions and how well academic research aligns with policy-relevant issues.

🎯 Objectives
Map dominant themes in Women’s Studies doctoral research
Identify regional and thematic gaps in women-centric scholarship
Compare machine-generated topics with manual qualitative coding
Assess relevance of academic research to policy concerns

🗂 Data

Source: Shodhganga (INFLIBNET) doctoral thesis repository
Corpus: 1,277 PhD theses (2011–2020)
Text fields: Abstracts, findings, and recommendation chapters
Validation data: National Commission for Women (NCW) reports

⚠️ Raw thesis texts are not shared due to repository and copyright restrictions.

🧠 Methods

Text preprocessing (tokenization, stopword removal, stemming)
Latent Dirichlet Allocation (LDA) for topic modeling
Topic coherence–based model selection
Visualization using LDAvis and t-SNE
Manual thematic coding (NVivo) on a stratified sample

🧪 Key Outputs

Topic distributions across district, state, interstate, and national levels
Regional patterns in women-centric research focus
Comparison of machine-driven vs. theory-driven themes
Policy-relevant gaps in academic research

🛠 Tech Stack

Python / R
NLP libraries (NLTK / gensim)
LDAvis
NVivo (for manual coding) 
![Figure 2  Trends in Women Studies accross in India](https://github.com/user-attachments/assets/28cc12f0-85f6-4a2a-9396-70700bd86158)

Trends in women’s studies theses across India from the Sodhganga repository, 2011-2020. 

<img width="500" height="500" alt="Figure 3 Distribution Thesis accross Indias States" src="https://github.com/user-attachments/assets/a9fabcac-b000-41af-b202-89bac65585d1" />

Distribution of theses across Indian states and major cities

![Figure 4  Distribution of work sector of women centric theses](https://github.com/user-attachments/assets/f78fb32f-a285-4935-8839-f38412daec87)

Distribution of work sector of women centric theses.
