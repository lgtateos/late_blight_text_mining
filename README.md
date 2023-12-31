# late_blight_text_mining
Reconstructing Historic and Modern Potato Late Blight Outbreaks using Text Analytics

**1843 Outbreak Map Data.xlsx**, **1844 Outbreak Map Data.xlsx**, **1845 Outbreak Map Data.xlsx** spreadsheets contain passages related to outbreaks in the US between 1843 and 1845 of the potato disease later termed "late blight".   The data was automatically extracted from agricultural reports in 1843-1945 US Patent Office documents during those years using NLP and mapped with geoparsing.    The data was then manually curated.   The resulting curated datasets are posted here (Figure 3).

**dated_country_geotweets.csv** contains the Tweet URLs, dates, and country location as ISO3 code for Tweets returned from a 10 year (2012-2022) query for terms for late blight. The columns IsRetweet and ContainsEurekaMag are used to further filter these Tweets (Figure 4).

**geocoder_results_corrected_url.csv** contains the Tweet URLs and geolocations for the dataset of late blight reports extracted from Tweets (2012-2022) using supervised text classification and Named Entity Recognition with geocoding and manually validated (Figure 5).
