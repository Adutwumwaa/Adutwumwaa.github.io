## BATCH PROCESSING AND DATA MINING

**Project description:**This project investigates the top keywords companies within various cities in the US require in the resumes of data science candidates.Batch processing with PySpark is the  data processing framework utilized for this project.
 The datasets of interest were downloaded from the specifed s3 bucket and read with pyspark.The two(2) datasets were joined and n-gram generated to mine for the keywords. Two(2) spark dataframes were then formed as below:
{Ngram, City, Frequency}
{Ngram,industry,Frequency}

A visualization package,Matplotlib was then used to compare a role(data science) between 2 cities(New York and Atlanta)



