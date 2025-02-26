# NFL-Big-Data-Bowl-2024

Background:

The NFL Big Data Bowl is an annual competition that challenges data scientists to analyze NFL game data and build predictive models. The goal of the competition is to develop models that can be used to predict the outcome of future games.

About the dataset:

The dataset consists of next gen stats provided by the NFL Team, available freely to the public for their use. 

It contains data from all the 8 weeks played in the 2022 NFL Season. The data includes information on each play in each game, especially data concerned with the theme of the competition, tackling.

Process:

The first step involves importing the data into the Python notebook, and importing all the necessary libraries that will be useful for analysis. The libraries used for this project are : pandas, numpy, plotly, tqdm, matplotlib, seaborn, tablib, dash

The next step involves deriving a brief statistics, and removing further anomalies, if any.

After these two steps, the analysis of the data is kickstarted.

Analysis:

The overall analysis has been done keeping in mind the theme of this year's competition: tackling.

The First Part of the analysis includes a heads up over games and player's data, which includes important information like home vs away team results, score distribution between them, player position distribution, etc.

The next Part of the analysis is purely about tackling. It covers a variety of topics like tackles by player positions, tackle location, tackles resulting into penalties. More analysis has been done which gives an idea about how individual players fared with their tackles, fumples, misses, etc. A comparative analysis has also been made, showcasing player vs player tackles, and interactive analysis where the audience can select NFL ID and see how their favourite player made tackles over the field and their tackling speed.

Challenges:

The major challenge faced during the analysis of the dataset was it's size.  

The data is also imbalanced, as some of the outcomes are more frequent than others. For example, forced fumbles made by players is almost the same. This makes it difficult to build predictive models that can generalise well to different scenarios.

The dynamic and complex nature of the dataset, which involves interaction between multiple players and factors affecting the outcome of game, made it difficult to analyse it. The data also changes over time, as teams and players adapt their strategies and tactics to different situations and opponents.
