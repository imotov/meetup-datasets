The latest version of this dataset can be downloaded from 

https://data.boston.gov/dataset/crime-incident-reports-august-2015-to-date-source-new-system

To load this dataset into Elasticsearch v5.4 use the following command on Mac and Linux:

cat crime.csv | ../../logstash-5.4.2/bin/logstash -f logstash.conf

Or the following command on Windows:

type crime.csv | ..\..\logstash-5.4.2\bin\logstash -f logstash.conf
