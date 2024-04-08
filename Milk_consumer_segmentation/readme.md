## PROJECT: MILK CONSUMERS TYPES
Cluster analysis for consumer segmentation

Files:
Milk_clusters.py - full results
Результаты и описание работ сегментация потребителей молочных продуктов.pdf - brief presentation main points, consumer`s map and describing segments
кластеры описание.xls - work file with cluster`s discribing 


Bisness goals:
for developing milk business to make a plan brand development in company. Investigate milk consumers in Russia.

Research target:
identify comsumer types on russian milk market for devloping stragegy of clients brands

Data: Its results of quantitative survey milk buyers about behavior, design preferences, brands loyality, price and quality preferences.

Attachments: questionary (russian version with original format, english after automatic translation) and csv file - database

Data types: most parts of data are categorical variables.

RESEARCH PLAN & METHODS
1. Describe Target Audience: Gender, Age, City, Income
2. Purchase volume calculating
3. Consumer behavior: frequencies and correlation
      Promo, producer`s, new brands preference
      Design preferences
      Eco preferences
4. Claster analysis
    4.1 Reduction variables
        4.1.1. Reduction design preferences
            PCA
            MDS
            TruncatedSVD
        4.1.2. Reduction for consumer`s product preferences
            PCA
            MDS
            TruncatedSVD
        4.1.3. Check korrelation between design preferences and consumer`s product preferences
    4.2. Preparing data for main cluster analysis
    4.3. Cluster analysis (for different data sets)
        4.3.1. K-means method
        4.3.2. Agglomerative Hierarchical Clustering
        4.3.3. hdbscan method clasterisation
        4.3.4. Clusters descripption Compare results and clusters parametres
    4.4 Variables optimisation (delete part dates)
        Exclude non-characters (for different clusters) variables
        Filter by % positive answer
    4.5 Best model
Summary
