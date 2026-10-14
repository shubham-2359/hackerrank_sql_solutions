# Japanese Cities' Attributes

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

Query all attributes of every Japanese city in the **CITY** table. The **COUNTRYCODE** for Japan is `JPN`.  

The **CITY** table is described as follows:  
<img src="https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg" title="CITY.jpg" />

**Input Format**

 

**Constraints**

 

**Output Format**

## Solution

**Language:** db2  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-14T20:29:16.820Z  

```db2

/*
    Enter your query here and follow these instructions:
    1. Please append a semicolon ";" at the end of the query and enter your query in a single line to avoid error.
    2. The AS keyword causes errors, so follow this convention: "Select t.Field From table1 t" instead of "select t.Field From table1 AS t"
    3. Type your code immediately after comment. Don't leave any blank line.
*/SELECT * FROM CITY WHERE COUNTRYCODE = 'JPN';

```

---

[View on HackerRank](https://www.hackerrank.com/challenges/japanese-cities-attributes/problem)