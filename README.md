# NHL-WAR-GAR-SPAR-Delta-Model

This notebook contains 6 different type of models with roughly ~10 different type of model fitting algorithms fit for best accuracy. 
There is 3 models to predict YoY of WAR (Wins above Replacement), GAR (Goals above replacement), and SPAR (Standing Points above replacement) for Forwards and 3 of the same type of models for defensemen. 


The goal is to help identify players that are likely to have an improvement WAR, GAR, or SPAR YoY. The results of the model ended up being able to classify those players with high probability of a bounce back year. 

The results of the model are included in the following publication: https://arch.library.northwestern.edu/concern/parent/ks65hc477/file_sets/qf85nb595

The application of the model allows Hockey Operations to identify players who may have been cheap relative to their recent season's performance but are likely to have an improved following season. 

Data downloaded from EvolvingHockey.com


# Predicting NHL Player Types and Breakout Seasons 
MSDS 498: Capstone 
Greg Ackerman Quinn MacLean Sean Prentis

## Problem Statement 
Goal scoring is typically not sustainable year-over-year. This poses a unique challenge for player projections in an league with high salary constraints. Since the 2007/2008 season, only 22% of forwards were able to improve their relative team impact (SPAR) year-over-year. This drives the objective to accurately predict and classify the next breakout players in the NHL. In order to identify the breakout players, clustering is created in order to understand the players that exist. The clusters and models identify players that are overvalued/undervalued based on their current salary structure. 
![image](https://user-images.githubusercontent.com/20390351/144778846-34b629ba-a3d5-48d3-bc32-d69a8901ac15.png)

## Player Clusters & Genes
Using a PCA K-means, six clusters (each) for Forwards and Defensemen were discovered 

High-End Offensive Forwards and Offensive Defensemen represent the highest caliber players in the NHL (i.e. Connor McDavid, Erik Karlsson)

Adding 1 High-End Offensive Forward to a line adds nearly 0.5 Goals for per 60 minutes
2019/20 TB Lightning have a line with 3 high-end offensive forwards, which score nearly ~4 goals per 60 minutes (Stamkos, Kucherov, Point) and rank as the highest scoring team

Some of the top producing defensive pairings have at least one two-way defensemen
Example: SJ Sharks duo Brendan Dillon (Two-Way Defensemen) and Erik Karlsson (Offensive Defensemen) are top in offensive production![image](https://user-images.githubusercontent.com/20390351/144778894-58a69100-d8a3-48c8-b2ce-31d97fd79dca.png)



