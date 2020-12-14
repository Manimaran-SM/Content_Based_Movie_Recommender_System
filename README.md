<h1 align="center"> Content_Based_Movie_Recommender_System
</h1>

* [Overview](#Overview)
   * [Introduction](#Introduction)
   * [Algorithm](#Algorithm_Used)
   * [Similarity Measure](#Cosine_Similarity_Measure)

* [Guide](#Guide)
  * [System Configuration](#System_Configuration)
  * [Pre-requisite](#Prerequisite)
  * [Procedure](#Procedure)
  * [Dataset](#Dataset)
  * [LiveDemo](#LiveDemo)

# Overview:
## Introduction
  >* 

## Algorithm_Used
  >* 

## Cosine_Similarity_Measure
  >*  Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. 
  >*  The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.
  >*  For more details about Cosine Similarity, click [here](https://www.machinelearningplus.com/nlp/cosine-similarity/)
  >*  Alternate to Cosine Similarity
      * Euclidean Distance
      * Manhattan Distance
      * Cosine Distance
      * Jaccard Similarity
      
  <img align ="center" src="https://www.machinelearningplus.com/wp-content/uploads/2018/10/soft-cosine-1024x489.png?ezimgfmt=ng:webp/ngcb3" alt="csoine_similarity">
  </img>
  
# Guide:

## System_Configuration
  >* Graphic card: NVIDIA GeForce GTX1050
  >* CPU: Intel(R) Core(TM) i7-8750H CPU @ 2.20GHz
  >* RAM: 8GB
  >* Disksapce: 1TB

## Prerequisite
Install Numpy with:

```
pip install numpy
```
Install Pandas with:

```
pip install pandas
```
Install Sklearn with:

```
pip install scikit-learn
```
Install Pickle with:

```
pip install pickle
```
Install nltk with:

```
pip install nltk
```
Install flask with:

```
pip install flask
```
Install request with:

```
pip install request
```
Install bs4 with:

```
pip install bs4
```
Install urllib with:

```
pip install urllib
```
## Note:
  >* For more details abou the packages used, Refer [![requirement](https://img.shields.io/badge/main.py-pink.svg?style=flat&logo=appveyor)](https://github.com/Manimaran-SM/Content_Based_Movie_Recommender_System/blob/master/requirements.txt)

## Procedure
  >* Click clone/download
  >* If you github desktop click open in desktop hit the clone button. 
  >* If you use download zip, then extract the zip file  
  >* If you want to use [HTTPS](https://github.com/Manimaran-SM/Content_Based_Movie_Recommender_System.git), then use the command
``` 
$ git clone https://github.com/Manimaran-SM/Content_Based_Movie_Recommender_System.git
```
  >* After completing the above steps, You can use jupyter notebook and python 3.8 to execute this code.
  >* Once after cloning the repository, Open the [![main.py](https://img.shields.io/badge/main.py-cyan.svg?style=flat&logo=appveyor)](https://github.com/Manimaran-SM/Content_Based_Movie_Recommender_System/blob/master/main.py) 
  >* If you have any problems regarding this repository or while opening or while running the files, feel free ask me [here](https://github.com/Manimaran-SM/Content_Based_Movie_Recommender_System/issues/new) with the issues you are facing.



## Dataset
  >* [List of movies in 2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)
  >* [List of movies in 2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)
  >* [List of movies in 2020](https://en.wikipedia.org/wiki/List_of_American_films_of_2020)
  >* [IMDB 5000 Movie Dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset) 
  >* [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)
  
## [LiveDemo](https://movie-recommendor-system.herokuapp.com/)
```
    https://movie-recommendor-system.herokuapp.com/
```
