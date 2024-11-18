# API-Pull

I need 10 years worth of info - For unitid 139940 - for fall enrollment - by level_of_study

The API is here: https://educationdata.urban.org/documentation/colleges.html#ipeds-enrollment-fall-enrollment-by-level-of-study-full-time-part-time-status-race-and-sex 
This one we would need 2013 - 2022

and here: https://educationdata.urban.org/documentation/colleges.html#ipeds-enrollment-fall-enrollment-by-level-of-study-full-time-part-time-status-age-categories-and-sex

I was not told which one to use, but either would work. 
This one we would need 2011 - 2020

The API has no API Key, and will also limit API calls to 10,000 records. However, there are alot more than 10,000 records. 
It also uses Pagination, so each year will have several URL pages.


The API reccomends I use Stata, but that is a $90 subscription. 
It offers other options to pull data - R, Pyton, HTML, and just downloading CSV's

They Python Script is the one that I cannot get to pull the correct information


How to use - "https://educationdata.urban.org/documentation/index.html#how_to_use"
FAQ Guide - https://urbaninstitute.github.io/education-data-faqs/

"Why am I getting only 10,000 results when I make an API call?

The API limits the number of records returned per page to 10,000. This ceiling prevents large data requests from slowing down the API for other users. To pull a full response that spans multiple pages, you will need to iterate over the pages and append the results together.

The R and Stata packages handle this process for you."
