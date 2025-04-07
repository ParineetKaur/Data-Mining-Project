# Data-Mining-Project

Contributor: Parneet Kaur and Lydia Myla

This project was done collaboratively for my Web and Data Mining course at Santa Clara University. It explores NBA player performance from the 2023-24 season using web-scraped statistics from [Basketball Reference](https://www.basketball-reference.com/). It uses a combination of Data Scraping, Preprocessing, Association Rules Mining, and Recommendation Algorithms. The goal was to uncover hidden patterns in player performance and develop a player similarity recommender. 

As mentioned the data was scraped from the webpage given using BeautifulSoup and Python requests. It includes key statistics such as: 
- Point Per Game (PPG)
- Assists (AST)
- Rebounds (TRB)
- Three-Point Percentage (3P%)

Our first step was using an Apriori Algorithm in order to mine basic associaiton rules (e.g High Scorer <-> Three-Point Shooter). Next, we used FP-Growth (i.e. FP-Trees) for scaled pattern mining. CHARM was used to extract only non-redundant, closed itemsets for more meaningful rule analysis. Finally, we built a content-based filtering system to recommend player with similar statistics. 

Some insights we gained from our analysis was that there exists a strong relationship between high scorers, three-point shooters, and playmakers. There are certain player archetypes such as "sharp-shooting playmakers" that emerged clearly from the data. Finally, players like Stephen Curry and LeBron James exemplify these high-performing multi-skill profiles, which related to real-life experiences. 

Thank you for checking out our project! We hope this project is insightful and inspiring for your own data science journey. ~ Parneet Kaur & Lydia Myla 🏀📊
