# BizCase 02 - Netflix-Data-Analysis Using Pandas and Matplotlib

# Business Problem:
Netflix is one of the most popular media and video streaming platforms. They have over 10000 movies or tv shows available on their platform. The dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc. Analyze the data and generate insights that could help Netflix in deciding which type of shows/movies to produce and how they can grow the business in different countries

# Business Case Study Highlights:
- Data cleaning: Dealing with list values/nested string values in the dataset
    - For example, A particular movie can belong to multiple Genres (like Drama, Comedy)
    - In such cases, the data were presented as follows: Dramas, Comedy
    - We have used Python string functions and pandas effectively to handle such data
- We have performed extensive EDA to address the business problem.
    - Throughout the notebook, we have frequently plotted a lot of graphs and used methods like pd.melt, pd.pivot, pd.pivot_table to restructure the       data in order to get the desired information
    - We have performed the EDA on movies and tv-shows separately and finally compared the two together

 # Business Insights & Recommendations:

- Business Insights
        As per Dataset most of the movies & TV Shows are directed by Rajiv Chilaka(19) followed by Raúl Campos and Jan Suter (18 each)
        Netflix started adding more and more TV Shows as the demand for the same is growing
        After 2019 there is a dip in the count of Movies and TV Shows, which may be the COVID effect
        Most directed movies on Netflix are directed by Rajiv Chilaka (As per Data Set)
        Highest percentile rating is for TV-MA
        The most number of Movies and TV Shows available in the US followed by INDIA
        Top 5 Genre is already analyzed, International Movies genre contains the highest number of Movies/TV Shows, i.e. 2624
        Estimate duration of any Show is around 200 minutes mostly
        August is the Month when most Movies/TV Shows are added to Netflix, followed by December and September
 - Recommendations
        As the popularity of TV Shows increases, Netflix should focus on TV Shows as well. This step can help Netflix to increase its user base
        India is the second largest user base for Netflix, Netflix should focus on more such content which can work efficiently in India
        Netflix should focus on the Comedy, Action & Adventure genres as these genres have great potential and are currently in a growing state           (On Netflix's platform)
        After Covid Period, i.e. after 2020, Netflix should focus on increasing the number of contents
