# web-scraping


## E-commerce product and sales data analysis  


## Table of Contents

1. [Introduction](#Introduction)
2. [Data Extracting](#Data-Extraction)
3. [Data Processing](#Data-Processing)
4. [Data Storing](#Data-Storing)
5. [End Note](#End-Note)

## Introduction: 

This project has two core part. One is to extract data from an E-commerce website (we used Amazon USA) and then store the extracted data into a database. From which data can be extracted very efficiently and insights can be formed. 

We worked on two segment Extracting data using python and storing and analysing the extractrd data using Mysql. 

Definition of the both segment can be seen with drop down below-

<details>
<summary>Web Scraping</summary>
<br>
Web scraping is data scraping used for extracting data from websites. The web scraping software may directly access the World Wide Web using the Hypertext Transfer Protocol or a web browser. 

</details>


<details>
<summary>Database Management</summary>
<br>
Database Management, allows  to organize, store and retrieve data from a computer. Database Management can also describe, the data storage, operations and security practices of a Database Administrator (DBA), throughout the life cycle of the data. Managing a database involves designing, implementing and supporting stored data, to maximize its value.
</details>

## Legal Issues:
As the data extracted here was for solely academic purpose and no business intention was not behiind it this scraping is until this point completely legal. 

## Data Extracting:

We used python libraries for extracting the data. The libraries used for scraping are below - 

---
**Libraries**

import fake_useragent

from selectorlib import Extractor

import requests

from fake_useragent import UserAgent

import json
from time import sleep

---

