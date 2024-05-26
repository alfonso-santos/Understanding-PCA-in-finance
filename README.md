# Understanding-PCA-in-finance

# Understanding PCA in Finance

This repository contains the code, data, and figures used for the article "Finally! Understanding What PCA Really Means in Finance."

## Abstract

In this study, we analyze the interpretation of eigenvectors as portfolios, known as eigenportfolios, and their fundamental characteristics. Our findings indicate that the returns of the first eigenportfolio have a very high correlation with overall market behavior, and its corresponding eigenvalue provides a measure of the portfolio’s risk (variance). The weights of the first eigenportfolio are inversely proportional to the variance of the individual assets, highlighting that larger capitalization assets, which typically have lower volatility, exert a greater influence on market movements. During market downturns, assets tend to align, leading to the first eigenportfolio explaining a larger proportion of market volatility. This alignment significantly increases the Eigenvalue Condition Number during bearish periods. Additionally, due to the orthogonality of eigenvectors, the second and third eigenportfolios have zero correlation with each other, allowing for the capture of distinct market trends. These insights underline the importance of monitoring these indicators for effective risk management and portfolio diversification, especially during times of market stress.

## Contents

- `src/`: Contains all the scripts and notebooks used for data analysis and figure generation.
- `data/`: Contains the datasets used in the study.
- `imgs/`: Contains the figures included in the article.

