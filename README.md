# News-Scrape
A web app that lets users leave comments on the latest news. Uses Mongoose and Cheerio to scrape news from The New York TImes.

## Synopsis

Whenever a user visits the site, the app will scrape stories from a news outlet of your choice. The data will  include a link to the story and the headline
Cheerio grabs the site content and uses Mongoose to save it to the MongoDB database.
All users can leave comments on the stories collected. Users can also delete whatever comments they want removed. All stored comments are visible to every user. The app uses Mongoose's model system to associate comments with particular articles.

## Project Structure

### NPM Packages  

  * express
  * express-handlebars
  * mongoose
  * body-parser
  * cheerio
  * request

### mLab (Deployment)

  * A emote MongoDB database that Heroku supports natively. 
  
## Motivation

Build an aplication that utilizes Scraping to populate the page and store the information with mongobd.

https://immense-falls-11276.herokuapp.com/
