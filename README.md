# NLP and Web Scraping Lab

This repository contains a demonstration of web scraping techniques, Natural Language Processing (NLP) pipeline, and various NLP tasks such as text cleaning, tokenization, stop words removal, discretization, normalization, stemming, lemmatization, parts-of-speech tagging, and Named Entity Recognition (NER) for Arabic language text.

## Table of Contents

- [Objective](#objective)
- [Tasks](#tasks)
- [Libraries Used](#libraries-used)
- [Web Scraping](#web-scraping)
- [Storing Raw Data](#storing-raw-data)
- [NLP Pipeline](#nlp-pipeline)
- [Synthesis](#synthesis)

## Objective

The main objective of this project is to demonstrate proficiency in web scraping and NLP techniques for Arabic language text. By scraping data from a website related to census processes in Morocco and applying various NLP tasks, we aim to showcase skills in data acquisition, preprocessing, and analysis specific to the Arabic language.

## Tasks

- Web scraping from [www.candidature-recensement.ma](https://www.candidature-recensement.ma/) to extract information about census conditions, steps, compensation, tasks, and frequently asked questions.
- Storing the raw data in MongoDB for further processing and retrieval.
- Preprocessing the Arabic text data through tokenization, stop words removal, normalization, stemming, lemmatization, and other techniques.
- Performing parts-of-speech tagging and Named Entity Recognition (NER) using Farasa library for Arabic language text.

## Libraries Used

- **requests**: For sending HTTP requests to the website and fetching the HTML content.
- **Beautiful Soup**: For parsing the HTML content and extracting relevant data from the website.
- **pymongo**: For interacting with the MongoDB database to store and retrieve the scraped data.
- **nltk**: For various NLP tasks such as tokenization, stop words removal, stemming, and lemmatization.
- **qalsadi**: For Arabic lemmatization.
- **farasa**: For Arabic language processing tasks including parts-of-speech tagging and Named Entity Recognition (NER).

## Web Scraping

We utilized the mentioned libraries in Python to scrape data from the [www.candidature-recensement.ma](https://www.candidature-recensement.ma/) website. The scraped data includes information about census conditions, steps, compensation, tasks, and frequently asked questions.

## Storing Raw Data

We stored the raw scraped data in a MongoDB database named "NLP" and a collection named "atelier". This allows for easy retrieval and further processing of the data.

## NLP Pipeline

The NLP pipeline involves several preprocessing steps such as tokenization, stop words removal, normalization, stemming, and lemmatization. We applied these techniques to the scraped Arabic text data to prepare it for analysis. Additionally, we performed parts-of-speech tagging and Named Entity Recognition (NER) using the Farasa library, specifically designed for Arabic language processing.

## Synthesis

Through this project, we gained valuable insights into web scraping, NLP techniques, and MongoDB database management specific to the Arabic language. The comprehensive NLP pipeline demonstrated proficiency in handling Arabic text data and performing various linguistic analysis tasks.
