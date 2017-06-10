# Thirukkural (திருக்குறள்) Dataset

The Tirukkural or Thirukkural (literally Sacred Verses), or shortly the Kural, is a classic Tamil sangam literature consisting of 1330 couplets or kurals, dealing with the everyday virtues of an individual.
Considered as chef d'oeuvre of both Indian and world literature, the Tirukkural is one of the most important works in the Tamil language.

This dataset is scraped from [Project Madurai](http://www.projectmadurai.org/pm_etexts/utf8/pmuni0001.html)

## About
This repo contains two files `chapters.txt` and `thirukkural.txt`

- thirukkural.txt
It contains all the 1330 couplets with each line containing a single couplet.
Each couplet has two lines with seven words. In this file the two lines are concatenated
into one using '$' as the delimiter for convenience.

- chapters.txt
This file contains all the chapter names, a total of 133.

### Note
If you wish to get thirukkural in a structured format (json) with rich content,
checkout this [repo](https://github.com/tk120404/thirukkural)
