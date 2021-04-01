# Data Engineering Programming Interview

## Q1: Basic File ETL: 
1)	Load TSV with headers file.
2)	Replace column evars with corresponding values 
3)	Remove unused columns.
4)	Save as new CSV.

## Q2: File ETL with bad data
1)  Load TSV with columns file
2)  Replace column names with mappings values
3)  Remove unused columns.
4) Save as new CSV.

## Q3: ETL Functions
1)  Create function to load incremental data
    a. Should log errors and validate accordingly.
2)  Will include missing day of data.
3)  Save as single aggregated csv.

## Q4: Advanced Time Series Data Mining
1) Use Q3 data output
2) Load Q3 csv files.
3) Groupby and sort into timeseries by date, name
4) Further process by aggregating time series by day, name, search_list where search_list is a list of search_terms performed in order by date
    a. Each row should represent one unique name per day with a list of search_terms
5) Save as CSV.

## Q5: Big Data Processing
Due to git file size limits, we are just going to have a discussion here on how to handle. We may or may not get to this point depending on how much time is allotted.

If time allows, take output of Q4 and use some big data processing techniques to split it out into daily files in a way to minimize memory usage and disk space.