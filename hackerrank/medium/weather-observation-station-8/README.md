# Weather Observation Station 8

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

Query the list of *CITY* names from **STATION** which have vowels (i.e., *a*, *e*, *i*, *o*, and *u*) as both their first *and* last characters. Your result cannot contain duplicates.


**Input Format**

The **STATION** table is described as follows:

<img src="https://s3.amazonaws.com/hr-challenge-images/9336/1449345840-5f0a551030-Station.jpg" title="Station.jpg" />

where *LAT\_N* is the northern latitude and *LONG\_W* is the western longitude.

**Constraints**

 

**Output Format**

## Solution

**Language:** db2  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-22T16:54:06.321Z  

```db2

/*
    Enter your query here and follow these instructions:
    1. Please append a semicolon ";" at the end of the query and enter your query in a single line to avoid error.
    2. The AS keyword causes errors, so follow this convention: "Select t.Field From table1 t" instead of "select t.Field From table1 AS t"
    3. Type your code immediately after comment. Don't leave any blank line.
*/SELECT DISTINCT CITY FROM STATION WHERE UPPER(SUBSTR(CITY, 1, 1)) IN ('A', 'E', 'I', 'O', 'U') AND LOWER(SUBSTR(CITY, LENGTH(CITY), 1)) IN ('a', 'e', 'i', 'o', 'u');

```

---

[View on HackerRank](https://www.hackerrank.com/challenges/weather-observation-station-8/problem)