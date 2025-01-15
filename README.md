# Dynamic-Credit-Migration-Based-Trading-Framework

The zip file file contains the following code files.
1) KMV -> where the DD(distance to default) and DF(default probability) are calculated and used in HMM.
2) HMM -> Historical credit ratings are predicted and assigns a numerical score.
3) Scoring -> A final credit scoring obatined combining numerical score of HMM and pure financial health score obatined from pure fundamental data.
4) creditrisk -> A hedging stratergy developed based on the continous score.
