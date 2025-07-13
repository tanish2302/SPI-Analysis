SPI-Analysis

Introduction

The Social Progress Index (SPI) is a composite index that measures and assesses the social and environmental performance of a country. It is designed to complement traditional measures of economic progress, such as GDP, by providing a more comprehensive view of a society's well-being and development.

Dataset

The CSV file for the dataset can be found here: https://github.com/rahul-bakshi/Global-Social-Progress-Index/blob/main/spi.csv

Aim and methodology

The aim of this analysis is to explore these questions:

    Identify countries with the best and worst SPI scores.
        The CSV file was originally ranked in the order of SPI rank therefore just head and tail functions provided the result. 02A
    How do different regions or continents compare in terms of their average SPI scores? Group the countries by regions or continents and calculate the mean SPI score for each group to identify regional disparities in social progress.
        In order to compare the continents, first made a dictionary mapping the countries with their respective continents and then plotted a bar graph showcasing the variation in spi_score. 03A
    Is there any correlation between the SPI score and individual components (e.g., basic human needs, well-being, opportunities, etc.)? Perform a correlation analysis to determine which specific factors have a stronger relationship with the overall SPI score.
        Plotted a correlation matrix, all of the attributes were highly related therefore decided to take the top 4 highly correlated attributes to consider in further analysis. 04A
    Conduct a comparative analysis of the continent with the highest average SPI score with the continent with the lowest average SPI score.
        From 03A it was confirmed that Europe has the highest average SPI score and Africa has the lowest. Filtered data for just these two continents and studied the variation in top highly correlated attributes found in 04A. 05A
    Can we classify countries into different social progress categories based on their SPI scores (e.g., low, medium, high)? Apply clustering algorithms or create bins to group countries according to their SPI scores and analyze the characteristics of each cluster.
        Used K-Means clustering to make 3 clusters of high, medium and low SPI scores and found insights on high clusters. 06A

Key Insights

    Europe as a continent has the best SPI score.

    Africa ranks lowest in SPI score.

    visualization (5)

    Top 4 factors affecting the SPI score are
        Wellbeing
        Opportunity
        Access to advanced education
        Access to information and communication

    image

    Africa can improve its SPI score by making improvements in its education and information and communication sector. visualization (6)

    57 countries out of 168 fall under the category of High SPI score

    61% of High SPI-scoring countries are in Europe.

    Africa only has 1 country in the High SPI category and that is Mauritius.

