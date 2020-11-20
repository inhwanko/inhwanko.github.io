---
layout: post
title: Climate Negotiation Text Project
tags: [test]
comments: true
---


## Detecting the evolving key UNFCCC principles in the making of Paris Agreement through automated text analysis on ADP bloc statements  

Inhwan Ko, Department of Political Science, University of Washington  
Jiwon Park, Graduate School of Green Growth, Korea Advanced Institute of Science and Technology  
Hyunseon Park, Graduate School of Environmental Studies, Seoul National University  
Kyungmin Lee, Biden School of Public Policy and Administration, University of Delaware  
 
### Abstract  

Negotiators in the making of the Paris Agreement had to face several challenges different from when their predecessors faced when making the UNFCCC. These challenges include (1) a new interpretation on the UNFCCC principles, such as the North-South divide or CBDR-RC (common but differentiated responsibility and respective capabilities), and (2) the emergence of new negotiation blocs such as AILAC (Association of Independent Latin American and Caribbean Countries) or LMDC (Like-Minded Developing Countries). Previous studies suggested that new interpretations of the UNFCCC principles have converged into two positions, one arguing differentiated responsibility that upholds the North-South divide (DR), and the other arguing shared responsibility that intends to overcome its divide (SR). Yet, we lack a systematic explanation on how these different blocs endorsed different interpretations on the UNFCCC principles on what basis. Using an unsupervised text scaling approach called wordfish, we place negotiation blocs on a uni-dimensional spectrum, with one extreme being DR and the other being SR, based on their statements during the ADP (Ad-hoc Working Group on Durban Platform) sessions. This enables a cross-sectional and time-series comparison of blocs’ positions on the new UNFCCC principles in the process of making the Paris Agreement, and helps explain what factors influence their positioning. Finally, we compare our findings with those using different automated text analysis methods and suggest future research questions.   

### Policy relevance  

We contribute to the understanding of the new political landscape for climate change negotiation by covering more negotiation blocs than previous literature has covered. Also, questioning the validity and usefulness of automated text analysis methods, we offer a new approach which can help us better understand positional differences among negotiation blocs with large textual data. This approach can be further expanded to analyze not only negotiation blocs’ but country Parties’ statements to ask compelling questions such as under what conditions country Parties’ positions deviate from their affiliated negotiation blocs. It can also be expanded to treaty negotiation cases in various issue-areas such as environment or human rights. Finally, by publicly providing our codes and results, our analysis serves as a basis for tools that help policymakers and analysts efficiently detect and keep track of positions of different political actors after the Paris Agreement was signed in 2015.   

Keywords: climate change negotiation, UNFCCC, negotiation bloc, North-South, CBDR-RC, ADP, text-as-data, automated text analysis, wordfish

## Key Preliminary Findings

### Figure 1. Point Estimates of Positions estimated from Country Bloc ADP Statements

![alt text](/assets/img/score_groups.JPG)  

### Figure 2. Time-Series Variation of Positions by Country Groups, ADP 2-1 to 2-12, with 95% Confidence Intervals (by Bootstrap)

![alt text](/assets/img/score_time.JPG)    


In two figures above, scores represent the position of country blocs toward the UNFCCC principle of CBDR-RC. Negative values indicate the position toward differentiated responsibilities across countries depending on their historical GHG emissions, and positive values indicate the position toward shared responsibilities regardless thereof. Wordfish uses unsupervised methods to scale these positions based on the word counts. Words associated with negative values are "differentiation," "commitments," "mandate," "kyoto," (Kyoto Protocol), while those associated with positive values are "shared," "collective," "balanced," "threats," "loss" and "damage."

