# Twitter-Data-Cleaning-Project
## overview
- Focus on this project was to clean data so it could be used for analysis.

## Gathering Data
The first CSV file was provided from Udacity. Using the requests library, I gathered a tsv file of the animal prodictions. Using the twitter id's
in the inital csv file 'twitter-archive-advanced' I used twitters API, tweepy, iterating through the twitter id's in my file to gather addtional data,
and stored it in a txt file.
## Assessing The Data
After collectiing the data, it was converted to a pandas dataframe, and assessed programically as well as visually on a spread sheet to identify areas for 
cleaning in order to preform visualizations. The assessment organized issues into 2 categories:
  - Quality issues
  - tidiness issues

## Cleaning The Data
After identifying what needed cleaning, this was the step of actually cleaning the data for anaylsis.
The new data was then stored into a new csv file.

## Analysing the data
There were some analysis made on the data to show that the data was ready for more in-depth analysis.
