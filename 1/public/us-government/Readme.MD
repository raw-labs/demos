## US Government - Legislators


See accompanying [Create Your First API Video](https://raw-labs.com/resource/create-your-first-api-in-4-minutes/)  and [Product Walkthrough Video](https://raw-labs.com/resource/raw-labs-data-sharing-overview-video/)


  Uses Free open data from https://theunitedstates.io plus Twitter and Google APIs 

**US Legislators (current)**

  List of current US Legislators - optional parameters to filter include type, state, party
  
  https://api.raw-labs.com/examples/1/public/us-government/legislators - returns all<br>
  https://api.raw-labs.com/examples/1/public/us-government/legislators?state=CA&type=rep&party=Democrat - Californian, Democrats in House of Representatives

**Sentiment Analysis on Tweets from US Legislators**

  Returns Recent tweets from Twitter, and runs Google Sentiment Analysis on the content of those tweets. 
  Output structure is the raw form from Googles Language API. 

  https://api.raw-labs.com/examples/1/public/us-government/legislators-tweets-sentiment?state=CA&keywordList=job,jobs,employment,economy<br>
  https://api.raw-labs.com/examples/1/public/us-government/legislators-tweets-sentiment?state=NY,NJ&type=sen
  
**Summaries (current & historical)**
  
  summaries of male to female legislators across all current and historical data. 
  These are good examples of union'ing two data structures, creating a summary function as a re-usable intermediate dataset.
  
  https://api.raw-labs.com/examples/1/public/us-government/summary/by-state?states_list=CA,NV
  https://api.raw-labs.com/examples/1/public/us-government/summary/by-party-house?party=Democrat
  
