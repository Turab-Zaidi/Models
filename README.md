# Models
This repository contains two project
In textsummarizer.ipynb file, I have used transformer to summarize large chunks of data. I have also done machine translation in one of the summary where summary of the text is generated in Hindi language.
In main.ipynb file, I have created Q_A based prompt which provides answer to our query based upon the information provided. Here I have a provided a chunk of data to it and I am asking based upon it.
It is using text embedding to vectorize the text provided and is saving the data in AstraDB provided by DataStax . This database is built on top of Apache Cassandra and specializes in vector searches.
