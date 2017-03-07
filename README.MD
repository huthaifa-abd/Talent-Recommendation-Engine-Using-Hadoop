# Talent Recommendation Engine Using [Hadoop]

A Map Reduce Java application to crunch job posting data into a meaningful information and providing matching rates

 * Parallel Data Processing
 * Keyword Based Matching
 * Big Data Compatible

Please note : This solution requires a specific data structure please review the attached example , or use the C# crawler to get started.

https://github.com/huthaifa-abd/Indeed-Job-Posting-Crawler

To build the project please use apache maven and execute the command below in the source directory
```
mvn clean package
```

Upload the code to your hadoop cluster and run the following

```
yarn jar [JAR FILE NAME] org.apache.hadoop.huthaifa.trEngine [HDFS PATH TO DATA] [HDFS OUTPUT PATH]
```

Hope you find this solution useful :+1:

### Future Updates

 * General Optimizations
 * Separate input for candidate and job postings
 * Unit Testing
 * Add more cool features .
