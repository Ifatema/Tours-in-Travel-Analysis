<div align="center">
 <img src="2.png" alt="Tours & Attractions in Travel">
 <h2 align="center">Tours in Travel Analysis</h2>
 <p>Tours in Travel project, is a project for Data Scienc course.</p>
 <p>This project is aimed to answer these questions:
    <ol>
    <li> How does the tour type relates to the tour duration?</li>
    <li> How does the price per adult for the same tour type changes around the world?</li>
    </ol>
 </p>
    <br/>
 <p>The dataset was scraped from <a href='https://www.tripadvisor.com/'>tripadvisor.com</a> by using the google chrome extension <a href='https://chrome.google.com/webstore/detail/instant-data-scraper/ofaokhiedipichpaobibbnahnkdoiiah'>Instant Data Scraper</a>.</p>
    
 <p>How does the extension work?
 <ul>
    <li> Add the extension to chrome</li>
    <li> Go to <a href='https://www.tripadvisor.com/'>tripadvisor.com</a></li>
    <li> From the website select things to do button then enter the city</li>
    <li> Press the extension button and locate the next page button</li>
    <li> Press start crawling button</li>
    <li> Download it as .csv file</li>
 </ul>
 </p>
 <p>I did it for 38 cities globally, the cities are:
    Abu Dhabi, Al Ula, Antalya, Beijing, Berlin, Buenos Aires, Cairo, Cape Town, Chicago, Riyadh, Athens, Doha, Istanbul, Jeddah, Kuala Lumpur, London, Madrid, Marrakech, Mumbai, Muscat, NewYork, Orlando, Rio de Janeiro, Paris, Rome, Singapore, Shanghai, Seoul, Tokyo, Amsterdam, Barcelona, Hong Kong, Los Angeles, Las Vegas, Mexico City, Sydney, Toronto & Vienna </p>
 <p> After collecting each city separately, I've changed the columns name to be the same for all cities, and I dropped meaningless columns that have been collected automatically. Then, I combined the 38 datasets in one main dataset. 
 </p>
</div>
 <!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#data-dictionary">Data Dictionary</a></li>
    <li><a href="#exploratory-data-analysis">Contributors</a></li>
    <li><a href="#References">References</a></li>
  </ol>
</details>

## About The Project
The dataset contains information about tours collected from **tripadvisor.com**. 
Each row represents a Tour with a Link to the agency that provide the tour in tripadvisor website. Other columns contain Tour Type, Tour Duration, Tour Price, Price Per adult or group, Cancellation, Tour By (agency), City, Country and Image.


## Data Dictionar
- **Tour**: the tour name
- **Type**: the tour type such as Bus Tours, Full-day Tours & Adventure Tours...
- **Duration**: the tour duration in hours
- **Price**: the your price in US dollar $
- **Price Per**: per adult or per group
- **Cancellation**: if free cancellation or not
- **Tour By**: the agency that provide the tour
- **City**: city name
- **Country**: country name
- **Image**: the image in the tripadvisor.com for each tour.
- **Link**: link to the agency that provide the tour in tripadvisor website.

## Exploratory Data Analysis
Data columns (total 11 columns):
 #   Column          Non-Null Count  Dtype  
---  ------          --------------  -----  
 0   Tour            10524 non-null  object 
 1   Type            10524 non-null  object 
 2   Duration        10524 non-null  float32
 3   Price           10524 non-null  float32
 4   Price Per       10524 non-null  object 
 5   Cancellation    10524 non-null  object 
 6   Tour By         10524 non-null  object 
 7   City            10524 non-null  object 
 8   Country         10524 non-null  object 
 9   Image           10524 non-null  object 
 10  Link to agency  10524 non-null  object 

 10524 entries


 ## References

##### Data Sources
* [Tripadvisor.com](https://www.tripadvisor.com/)
* [Instant Data Scraper](https://chrome.google.com/webstore/detail/instant-data-scraper/ofaokhiedipichpaobibbnahnkdoiiah)

##### References
* [GitHub README Template](https://github.com/othneildrew/Best-README-Template)
* [Reading and Writing CSV Files in Python](https://www.learnbyexample.org/reading-and-writing-csv-files-in-python/)
* [How to combine two dataframe in Python – Pandas?](https://www.geeksforgeeks.org/how-to-combine-two-dataframe-in-python-pandas/#:~:text=Another%20way%20to%20combine%20DataFrames,join%20key(s)%E2%80%9D.)
* [Pandas recalculate index after a concatenation](https://stackoverflow.com/questions/35528119/pandas-recalculate-index-after-a-concatenation)
* [Pandas – Split Column by Delimiter](https://datascienceparichay.com/article/pandas-split-column-by-delimiter/#:~:text=Split%20column%20by%20delimiter%20into,True%20to%20the%20expand%20parameter.)
* [Replace nan with the same value of another column](https://stackoverflow.com/questions/29177498/python-pandas-replace-nan-in-one-column-with-value-from-corresponding-row-of-sec)
* [Pandas conditional multiplication](https://stackoverflow.com/questions/34803670/pandas-conditional-multiplication)
* [How to Change Font Size in Seaborn Plots (With Examples)](https://www.statology.org/seaborn-font-size/)
* [canva](https://www.canva.com/)
<p align="right">(<a href="#top">back to top</a>)</p>