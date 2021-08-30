# Wrangle-act
Wrangling data from multiple sources
Real-world data rarely comes clean. Using Python and its libraries, we gathered data from a variety of sources and in a variety of formats including (csv, text or json), assess its quality and tidiness, then clean it. Our wrangling is divided into three phases:  Gathering data,  Assessing data, and  Cleaning the data.
## Dataset: 
Our data is gathered by:
<li>downloadable csv file,</li>
<li>a flat file that we need to scrape from a given [URL](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv)</li>
<li>querying twitter API from twitter account [@dog_rates](https://twitter.com/dog_rates) and store each tweet's entire set of JSON data in a file called tweets_json2.txt file </li>

## Packages to be installed
- pandas
- tweepy
- OAuthHandler from tweepy
- os
- requests
- import Image from PIL
- import BytesIO from io
- import BeautifulSoup from bs4
- json
- import default_timer from timeit
- numpy
- matplotlib
