# SCP Foundation Wiki - NLP Exploration

![word_cloud](/images/cloud_words.png)

## Explore language patterns of the SCP Wiki

### This project will attempt to find patterns in the SCP submissions of the [SCP Foundation Wiki](https://scp-wiki.wikidot.com/) in 3 steps. To date: 

###### 1/ A scraping algorithm that scraps the text up to the SCP-2700 as well as users ratings:
   - The website framework changes a lot the more recent the SCP submissions are. A more flexible and robust scraping algorithm will be submitted soon
   - It is easy to enrich the current and future data with the tags and the number of discusssions at least. A commit will be submitted soon

###### 2/ Pre-processing of the data and basic NLP implementations 
   - To first structure the project, I only implemented to-date basic NLP algorithms
   
###### 3/ An Apache Spark implementation of some NLP algorithms through John Snow Labs SparkNLP. The implementation is done within Databriks
   - See https://github.com/JohnSnowLabs/spark-nlp-workshop/blob/master/tutorials/old_generation_notebooks/colab/4-%20Entity%20Recognizer%20DL.ipynb

