# Alphavirus-Epitopes
#### Data Mining Project to Predict Epitopes of Alphavirus


## Project Introduction

In early steps of development of vaccines, diagnostic tests and therapeutic interventions against infections, identification of <b>Linear B-cell epitopes</b> is very important. These are short protein fragments that are recognized by certain components of the immune system. It requires a lot of resources to carry out experimental discovery of epitopes and there has been use of computational methods over the past 3 decades to help in prioritizing candidates for characterization in the lab.

This project is based on predicting the <b>epitopes of Alphavirus</b> which is a genus of mosquito-borne viruses that includes pathogens of medical concert such as <b>Chikungunya</b> and other viruses that affect millions of people, mainly in the <b>Global South</b> but with the potential to migrate to the north due to climatic change.

The objective of this project is to develope an efficient <b>Data mining pipeline</b> to potentially predict new, previously unkown epitopes in viruses based on this genus.

### Data

More than one data of the same structure is used in this project. There will be an optimal tradeoff between data using a training data of a smaller amount of data coming from viruses that are more similar to our target ones, and using a lager volume of data coming from potentially different viruses.

More than one classification models will be created then assesed for performance metric using <b>Area under ROC curve (AUC)</b>. The performance metrics will then be compared to identify the one that <b>generalizes</b> better than the other(s). The best one will be used to draw <b>conclusions, make decisions and recommendations</b> in the project's <b>report</b>.
