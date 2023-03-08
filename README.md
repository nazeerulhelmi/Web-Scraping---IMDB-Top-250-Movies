# Web-Scraping-IMDB-Top-250-Movies

As I was doing the Netflix dashboard, I was wondering what are some great movies available out there that I haven't watched. So, I look it up at one of the common website for movie's rating, IMDB, to find out about it.

The project scrape data from IMDB website to get the list of top 250 movie based on its rating and converted it into an [Excel file](https://github.com/nazeerulhelmi/Web-Scraping-IMDB-Top-250-Movies/blob/main/IMDB%20Top%20250%20Movies.xlsx).

The tools used is ***python***, and involved the use of module such as '**BeautifulSoup**' to parse the HTML source code and '**requests**' to gain access to the website.

There are two python file here,
  1. [imdb_top_movie](https://github.com/nazeerulhelmi/Web-Scraping-IMDB-Top-250-Movies/blob/main/imdb_top_movie.ipynb) is the overall/final code to scrape the list
  2. [overview for loop](https://github.com/nazeerulhelmi/Web-Scraping-IMDB-Top-250-Movies/blob/main/overview%20for%20loop.ipynb) is the thought process, showing the result of line-by-line code while trying to scrape for the list
  
The result is the [IMDB Top 250 Movie.xlsx](https://github.com/nazeerulhelmi/Web-Scraping-IMDB-Top-250-Movies/blob/main/IMDB%20Top%20250%20Movies.xlsx) which was loaded using **openpyxl** module.
