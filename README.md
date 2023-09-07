# nba-rapm-datacollection-stat143

MOST/ALL Python Code is from https://github.com/rd11490/NBA_Tutorials

and R code is from https://github.com/anpatton/basic-nba-tutorials/blob/main/rapm/how_to_calculate_rapm.md

I've updated it to scrape the 2021-22 data in two scenarios - the first 500 games in the season and all games in the atlantic division.

If you're running the ipynb files to scrape yourself, good luck - there's a lot of games that just have errors you'll have to work through.

I'm working on having a set list of games that work in all that are scraped so you could run it and re-scrape the same files every time.

The RMD files clean the data that's already in the files, and the RAPM model file just requires you to select which aggregated dataset you want by changing the possession data in the line with the library calls
