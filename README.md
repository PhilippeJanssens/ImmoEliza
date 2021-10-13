# ImmoScraper

The goal of this project is to create web-scraping algorithms that can build datasets of real estate prices.

### Structure

The program currently has two functional scrapers and one in development.

1. [x] [immoweb](https://www.immoweb.be/fr)
2. [x] [immo elissa](https://immoelissa.be/)
3. [ ] [zimmo (*in development*)](https://www.zimmo.be/nl/)

### Tech

All libraries make extensive use of the *Selenium* library.

Scrapers are structured into 3 main methods:

- **readAdPage**: gathers all the data from each individual ad page
- **page_advert_urls**: gathers all the links to each individual ad of a search page
- **readPagination**: cycles through all the pages that contain all the links to individual pages.

### Roadmap

The structure we used can be applied to most real estate sites with minor alterations to the code.
Development of these individual scrapers is the next step.

Using *threading* has been applied on a number of different ways, but because of the amount of data
and speed of the collection is not used in our execution because of lack of memory errors.

### Installation

- Clone the repository / download the files. Open your terminal and navigate to this directory.
- Open a scraper with the notebook, and execute the cells you want.

### Use 

Inside the Jupyter Notebooks there will be cells with imports, classes and function that run them.
Run all the imports and classes first, then make the choice between working threaded or one at a time,
by running the correct cells.

### Credits

- mr. Data: @PhilippeJanssens
- ms. ScrapingMaster: @benoitmargx
- mr. HousesAreTooDamnExpensive: @manwithplan


