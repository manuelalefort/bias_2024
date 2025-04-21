# bias_2024
# Addressing Bias on the GGE on LAWS

This project seeks to map the way states addressed the issue of bias in Autonomous Weapons Systems (AWS) at the GGE on LAWS in 2024.

It is part of a wider project conducted by the InterAgency Institute that seeks to inform delegations in both Geneva and New York with more granularity in threshold concepts of the policy debate over AWS, focusing on International Security and Ethics. This project is financed by Stop Killer Robots.

In this GitHub page, we make available a detailed explanation of our methodology to support our findings on the bias debate, and also the database used, as a CSV (comma-separated values) file. We hope our work will lead to a more granular understanding of the discussions on the GGE and beyond.

For any questions, you may reach me at **manuela.lefort@interagency.institute**

---

## Methodology

From a database generated for our previous project containing all the discussions on the GGE on LAWS, we created a subcorpus based on a key-word list that would incorporate terms related to bias.

---

## Keywords to Identify Statements on Bias

`bias`, `societ*`, `existing`, `histor*`, `selection`,  
`program`, `develop`, `train`, `design`, `process`, `model`, `label`, `algorithm`, `divers*`,  
`automat*`, `cognitive`, `choice`, `user`, `loop`, `feedback`, `deploy`, `interact`

---

## Analytical Framework

Our objective is to understand how states addressed the issue of bias in military AI during the 2024 CCW discussions. For this end, we used the framework for the different typologies of bias in military AI systems proposed by Blanchard, A., & Bruun, L. (2024) [1]. The keywords were also selected based on the explanations of each typology given in their paper.

We proceeded to identify the statements which belonged to each typology proposed. With the subcorpus assembled, we trimmed the statements to remove all sentences that did not refer to bias.

For analytical clarity, **bias in society** and **bias in data processing and algorithm development** were grouped together, as both refer to structural or technical issues within the system — either stemming from societal inequalities or introduced during the design and development of AI. In contrast, **bias in use** was considered separately, as it refers to issues that arise during the deployment and interaction with the system, often due to context-specific factors or unanticipated user behavior.

---

## Typology Table

| Typology           | Keywords                                                                 |
|--------------------|--------------------------------------------------------------------------|
| **TIP 1+2**         | bias, societ*, existing, histor*, selection, program, develop, train, design, process, model, label, algorithm, divers*, rac*, gender, discriminat* |
| **TIP 3**           | automat*, cognitive, user, deploy, interact                             |

---

## Reference

\[1\] Blanchard, A., & Bruun, L. (2024). *Bias in Military Artificial Intelligence: A Typology of Sources*. Stockholm International Peace Research Institute.
