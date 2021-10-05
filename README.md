<link rel="stylesheet" type = "text/css" href="style.css">

## Daniel Aguirre

*An Aspiring Data Analyst*

## Tokyo Olympics 2020

**This project involved scraping data from a website to create a dataframe showcasing athletes that perfomed in the olympics and medals that were won. Then taking the dataframe and creating a visualization.**

**Jupyter Notebook**

[![img](https://github.com/Daniel-Aguirre-11/Portfolio/blob/main/Jupyter_Notebook_Thumbnail.png?raw=true)](https://github.com/Daniel-Aguirre-11/Olympics-Project/blob/main/Scraping%20olympics%20data.ipynb)

I usedJupyter Notebook with Python to scrape the olympics website with BeautifulSoup for data. I added titles and comments to certain blocks of code to help understand what they do, along with my thought process. The end result was to create a table of information on each athlete (name, age, team, event, medal, etc.) so that I could answer some questions I had about the Olympics.

**SQL**

[![img](https://github.com/Daniel-Aguirre-11/Portfolio/blob/main/sql_thumbnail.png?raw=true)](https://github.com/Daniel-Aguirre-11/Olympics-Project/blob/main/2020_Tokyo_olympics.sql)

I then started using SQL to answer the questions I had about the data. How many medals did each team win? How many male vs female athletes? How old/young where the participants? etc. I then started writing some qeuries to anser my questions. I landed on the bigest question I came up with, which was "How many medals where won by each Team?". This question is what I decided to visualize in Tableau.

**Tableau Visualization**

[![img](https://github.com/Daniel-Aguirre-11/Portfolio/blob/main/Tableau_thumbnail.png?raw=true)](https://public.tableau.com/views/TokyoOlympics2020_16320957724210/TokyoOlypmics?:language=en-US&:display_count=n&:origin=viz_share_link)

I created a simple interactive map dashboard that would display the total medals earned along with the individual athletes for that team. When a location is clicked on the map, that teams information will populate on the right side of the dashboard.

Tools Used for this project:
* **Python libriaries used:** Pandas, Beautifulsoup, Selenium
* **SQL:** SQL Server Management Studio
* **Tableau**

Sources:
* [www.olympics.com](https://olympics.com/)
