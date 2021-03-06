# Wikipedia Big Data Analysis

This analysis consists of using big data tools to answer questions about datasets from Wikipedia. There are a series of analysis questions, answered using Hive and MapReduce. The tools used are determined based on the context for each question. The output of the analysis includes MapReduce jarfiles and .hql files so that the analysis is a repeatable process that works on a larger dataset.

# Technologies Used

1.  Hadoop
2.  HDFS
3.  YARN
4.  MapReduce
5.  Hive
6.  TEZ
7.  Git Bash

# Features
1.  Process the downloaded data analyze the datasets.
1.  Find, organize, and format pageviews on any given day.
2.  Follow clickstreams to find relative frequencies of different pages.
3.  Find the different way to analyze the most internal search link fraction of hotel california.


# Getting Started

Most of the code was done using HQL in a Hive GUI interface via Data Analysis studio

1. Download Hortonworks community Edition -https://www.cloudera.com/downloads/hortonworks-sandbox/hdp.html
2. Install Hortonworks on your machine or virtual machine - https://www.virtualbox.org/wiki/Downloads
3. Download Git Bash on your computer - https://git-scm.com/downloads
4. Clone my code - git clone https://github.com/MANASWINI1591/BIG-DATA-PROJECT1.git
5. Setup a Hortonworks in virtual machine, import pageview and clickstream data in hdfs, and start queryin the with hive.

# Problem Statement

1. Which English wikipedia article got the most traffic on April 20, 2021?
2. What English wikipedia article has the largest fraction of its readers follow an internal link to another wikipedia article?
3. What series of wikipedia articles, starting with Hotel California, keeps the largest fraction of its readers clicking on internal links.
4. Find an example of an English wikipedia article that is relatively more popular in the Americas than elsewhere.There is no location data associated with the wikipedia            pageviews data, but there are timestamps. You'll need to make some assumptions about internet usage over the hours of the day.

# Usage

1. The HQL commands can be used on similar large datasets, specifically those found in Wikipedia dumps - https://dumps.wikimedia.org/
2. This script was designed to answer all sorts of questions pertaining to big data.

# Reference

* https://github.com/samye760/Wikipedia-Big-Data-Analysis 

