# Task-2
Data Vizualization

Average Sales per Game = 
DIVIDE( [Total Global Sales], [Total Games] )
Platform Sales = SUM(vgsales[Global_Sales])
Sales Rank = 
RANKX(ALL(vgsales[Name]),
    SUM(vgsales[Global_Sales]),
    ,
    DESC,
    DENSE
Total Games = DISTINCTCOUNT(vgsales[Name])
Total Publishers = DISTINCTCOUNT(vgsales[Publisher])
