# API-Pull

The API is here: https://educationdata.urban.org/documentation/colleges.html#ipeds-enrollment-fall-enrollment-by-level-of-study-full-time-part-time-status-race-and-sex

and here: https://educationdata.urban.org/documentation/colleges.html#ipeds-enrollment-fall-enrollment-by-level-of-study-full-time-part-time-status-age-categories-and-sex

The API has no API Key, and will also limit API calls to 10,000 records. However, there are alot more than 10,000 records. 

They Python Script is the one that I cannot get to pull the correct information


FAQ Guide - https://urbaninstitute.github.io/education-data-faqs/

"Why am I getting only 10,000 results when I make an API call?

The API limits the number of records returned per page to 10,000. This ceiling prevents large data requests from slowing down the API for other users. To pull a full response that spans multiple pages, you will need to iterate over the pages and append the results together.

The R and Stata packages handle this process for you."
