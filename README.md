<h1> Movies-Data-Web-Scrapping </h1>
<h3> Introduction </h3>
In this project, the main aim is to create an american films dataset such that it contains 'movie title', 'genres', 'director name', and 'top 3 cast'.

The data includes american movies from 1874 to 2021. (very few are removed during preprocessing) 

<h3> What I did? </h3>
<p>
The dataset('movies_upto_2021') I shared in the datasets folder is not completely web scraped but I have taken <a href='https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset'>the movies dataset</a> from kaggle which contains data upto 2017 and preprocessed it.

After then I webscrapped the rest of the movies data (i.e., 2018 - 2021) through wikipedia and TMDb API.

Here are the links through which I web scrapped the movie title.
* <a href='https://en.wikipedia.org/wiki/List_of_American_films_of_2018'>2018 Movies</a>
* <a href='https://en.wikipedia.org/wiki/List_of_American_films_of_2019'>2019 Movies</a>
* <a href='https://en.wikipedia.org/wiki/List_of_American_films_of_2020'>2020 Movies</a>
* <a href='https://en.wikipedia.org/wiki/List_of_American_films_of_2021'>2021 Movies</a>

For genres, director, and movie cast, I have used TMDb API and processed it to get the results I desired.

<b>Note:</b> Due to the file size I have not uploaded every dataset. Kindly, go through <b>'readme.md'</b> in the <b>'datasets'</b> folder for more information.
</p>
