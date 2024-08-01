---
title: "Sleep stages classification using EOG"
excerpt: "The goal of this project was to classify sleep stages using only EOG<br/><img src='/images/sleep_stage.png'>"
collection: portfolio
---

## 💤 💤 💤

For this group work, I developed a Best-RQ framework to classify sleep stages. I then trained several networks with this framework and compared the results between EOG only, EOG + EEG, EOG spectrograms. I also developed all the preprocessing scripts and the utils function (One of the network used was similar to PainAttNet [https://www.frontiersin.org/journals/physiology/articles/10.3389/fphys.2023.1294577/full]). The results were not really conclusive due to an unbalanced data set, person dependent data and noisy data. Some ideas to improve this framework were suggested in our report, such as using networks with memory to decode the information, weighting the different classes, etc.


<br/><img src='/images/pain_att.jpg'>
