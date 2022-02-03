![RAW Labs](https://avatars.githubusercontent.com/u/11390046?s=100&v=4)
# Examples Data Products

The following are data products examples built using RAW. More detail and the code is available within these sub-directories<p>

Comments and suggestions are welcome: feel free to file GitHub Issues or email us at hello@raw-labs.com

* [Movies](./1/public/movies)
* [Olympic Games](./1/public/olympic-games)
* [Recently Updated Sitemap Pages](./1/public/sitemap)
* [Value at Risk](./1/public/value-at-risk)

Read our Blogs and Tutorials too:
https://www.raw-labs.com/blog

Follow us on on Twitter:
https://twitter.com/raw_labs

## [Movies](./1/public/movies)

Endpoints to query data from a copy of the Wikipedia's movie dataset, stored on GitHub.

Movies can be queried by title<p>https://api.raw-labs.com/examples/1/public/movies/movies-by-title?title=river 

or by year<p>https://api.raw-labs.com/examples/1/public/movies/movies-by-year?year=2000

## [Olympic Games](./1/public/olympic-games)

Endpoints combine "open" data hosted on DataHub, as well as files stored on an S3 bucket.

Medals per country<p>https://api.raw-labs.com/examples/1/public/olympic-games/country-medals?country_name=Germany

Medals per athlete (there's a [video](https://www.youtube.com/watch?v=zgBW5kHK-Vo) about this endpoint)<p>https://api.raw-labs.com/demos/1/public/olympic-games/athlete-data?athlete_name=BURKE,%20Thomas

Gold medals per country<p>https://api.raw-labs.com/examples/1/public/olympic-games/country-gold-medals?country_name=Germany

## [Recently updated web pages](./1/public/sitemap)
  
Retrieve last updated web pages from a website sitemap:

https://api.raw-labs.com/examples/1/public/sitemap/recentpages?website=https://virgingalactic.com
 
## [Value at Risk](./1/public/value-at-risk)
  
Example showing resource-intensive data products involving calculations on sizeable data:

https://api.raw-labs.com/examples/1/public/value-at-risk/index-var?index=^DJI - Dow Jones 30 stocks

https://api.raw-labs.com/examples/1/public/value-at-risk/index-var?index=^GSPC - S&P 500 stocks

https://api.raw-labs.com/examples/1/public/value-at-risk/index-var?index=^IXIC - Nasdaq 100 stocks

