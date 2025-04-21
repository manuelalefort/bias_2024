# Addressing Bias on the GGE on LAWS

This project seeks to map the way states addressed the issue of bias in Autonomous Weapons Systems (AWS) at the GGE on LAWS in 2024.

It is part of a wider project conducted by the [InterAgency Institute](https://interagency.institute/) that seeks to inform delegations in both Geneva and New York with more granularity in threshold concepts of the policy debate over AWS, focusing on International Security and Ethics. This project is financed by Stop Killer Robots.

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
**To avoid pre-existing bias regarding the position of each delegation, the metadata (delegation, session, time, and date) were hidden during this process.**

For analytical clarity, **bias in society** and **bias in data processing and algorithm development** were grouped together, as both refer to structural or technical issues within the system — either stemming from societal inequalities or introduced during the design and development of AI. In contrast, **bias in use** was considered separately, as it refers to issues that arise during the deployment and interaction with the system, often due to context-specific factors or unanticipated user behavior.

---

## Typology Table

| Typology                                           | Keywords                                                                 |
|----------------------------------------------------|--------------------------------------------------------------------------|
| **Bias in society and in data processing and development** | bias, societ*, existing, histor*, selection, program, develop, train, design, process, model, label, algorithm, divers*, rac*, gender, discriminat* |
| **Bias in use**                                    | automat*, cognitive, user, deploy, interact                              |

---

## Reference

[1] Blanchard, A., & Bruun, L. (2024). *Bias in Military Artificial Intelligence: A Typology of Sources*. Stockholm International Peace Research Institute. Available at: https://www.sipri.org/publications/2024/sipri-background-papers/bias-military-artificial-intelligence

---

## Copyright

Copyright (c) 2025 InterAgency Institute

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
