# Cheerio-Scraper
Week 18 Assignment

# All the News That's Fit to Scrape

### Overview

In this assignment, I created a web app that lets users view and leave comments on the latest news.  Articles are scraped from another another site.

### How To Use

* Whenever a user visits the site, the app allows them to scrape the latest stories and display them. Each scraped article is saved to the application database, with no dupliate entries created. The app scrapes and displays the following information for each article:

     * Headline - the title of the article

     * Summary - a short summary of the article

     * URL - the url to the original article

* Users can leave comments on the articles displayed and revisit them later. The comments are saved to the database as well and associated with their articles. Users can also delete comments left on articles. All stored comments is visible to every user.

## Built With

  * [express](https://www.npmjs.com/package/express)
  * [express-handlebars](https://www.npmjs.com/package/express-handlebars)
  * [mongoose](https://www.npmjs.com/package/mongoose)
  * [cheerio](https://www.npmjs.com/package/cheerio)
  * [axios](https://www.npmjs.com/package/axios)
  * [morgan](https://www.npmjs.com/package/morgan)

## Deployed on

  * [Heroku](https://www.heroku.com/)
    Utilizing:
  * [MongoDB](https://www.mongodb.com/)
  * [mLab](https://mlab.com/)

## Author
* David Jacovini

