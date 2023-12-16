# jangwonyoung

# ALL PROGRESS REPORT + UPDATES + HOW TO RUN IS IN THIS README
# VIDEO LINK

## What are the names and NetIDs of all your team members? Who is the captain? The captain will have more administrative duties than team members.
Manikandan Nagarathnam - mnn3, 
Pascal Adhikary - pascala2, 
Team Captain - Pascal

## What topic have you chosen? Why is it a problem? How does it relate to the theme and to the class?
We have chosen, Theme 5 Free Topics, Youtube Comment Sentiment Analysis, which is relevant because Youtube removed their dislikes, so it is often hard to discern whether people actually like a given video or not. We need to extract large bodies of text from the comment section of a video, and perform analysis on it to determine what sentiment it shows. 

## Briefly describe any datasets, algorithms or techniques you plan to use
We will just scrape the comments section of several hand picked videos, and utilize natural language processing algorithms/concepts such as stemming, tokenization, and POS tagging in combination with sentiment analysis libraries. 

## How will you demonstrate that your approach will work as expected? 
There are currently other programs that are able to estimate the amount of dislikes on a youtube video, so we can compare the sentiment that our project finds and see if it correlates to the estimated like/dislike ratio.

## Which programming language do you plan to use?
Python/JavaScript

## Milestones
Nov 8 - find and scrape videos  
Nov 13 - conduct introductory research  
Nov 24 - implement natural language algorithms onto the  
Dec 5 - implement and integrate algorithm with extension functionality  
Due date - clear up any bugs  

## Please justify that the workload of your topic is at least 20*N hours, N being the total number of students in your team. You may list the main tasks to be completed, and the estimated time cost for each task.
Pick videos to scrape - 1hr, 
Build Comment Section Scraper - 5hr, 
Perform Research and Implement NLP Algorithms - 25hr, 
Testing and anticipated debugging - 5hr, 
Integrate Backend code with extension - 10hr, 

## Progress Report 11/19/23:
1) Completed Tasks: We developed a comment scraping program that's capable of taking a file containing youtube video ids and scraping the comments of each of the associated videos. We then write each of the video's comments into a csv to store and later use. We have also started to conduct research into how we're going to perform sentiment analysis, but have yet to implement them.
2) The main tasks that are pending are to implement our natural language algorithms, package everything we have into an extension format, and bug test.
3) The first part of this project has been relatively easy, but we expect to face much more challenges when implementing our algorithms and when trying to put it into an extension, as this is something neither of us has very much experience in.

## Setup Instructions

To run this code, please perform these steps.
1) Clone the repo
2) Open the python notebook in Colab
3) Replace the API key with your google cloud youtube API key
4) Fill the inputs text file with the youtube id's you are interested in. The videos must have commments enabled for the program to work.
5) Pull the text file into your Colab notebook
6) Run the code cell by cell
7) Please also refer to the video link at the top of this file for help

## Conclusion, Self Evaluation, Final Report

We were able to create a final deliverable that can take any youtube video and via sentiment analysis on the youtube comments, give an estimate for the amount of dislikes.

This project was really interesting because we were able to investigate and understand what was going on under the hood in a lot of the popular python libraries. Thanks to what we learned in class, we were able to actually understand the methods such as vectorization and TF-IDF at play. In addition, the real world use of APIs taught us a lot about handling the response data. Initially, we wanted to make this an extension, but due to Chrome's strict rules on developers and uploading to the web store we were unable to within the class's time frame.
