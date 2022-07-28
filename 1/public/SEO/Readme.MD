## SEO 


## Historical Search Volume for Google Searches:

API capablity using DataforSEO.com<br>
Endpoint returns Historical Searches for Keywords on Google, by Month.
   
   Parameters:<br>
    - keywords: a list of comma-separated keywords, i.e. "tesla,bmw" (Required)<br>
    - language_code: uses the iso standard, i.e. "en" (one of this or language_name is required)<br>
    - language_name:  i.e. "French" (one of this or language_code is required)<br>
    - location_code: uses the values from dataforseo.com, i.e. 2840 is United States (one of this or location_name is required)<br>
    - location_name:  i.e. "United States" (one of this or location_code is required) <br>
    - include_serp_info: defaults to false, if true will include the SERP info results<br>
    
    Note this API uses DataForSEO API, see: https://docs.dataforseo.com/v3/keywords_data/google_ads/search_volume/live/ for more details
    
Example:

https://api.raw-labs.com/examples/1/public/SEO/historical-search-vol?keywords=tesla,bmw&language_code=en&location_name=United%20States

