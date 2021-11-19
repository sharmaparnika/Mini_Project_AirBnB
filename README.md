# AirBnB Pro

<img width="557" alt="logo" src="https://user-images.githubusercontent.com/73773202/142670106-152ababe-ae2d-4a6d-9a6c-177a45338189.png">
The only proffesional you need for all your AirBnB deeds.
Planning for a "Stay-Cation" but don't know the perfect place that will give you the homely feel and also fullfill your tourist needs?

AirBnB Pro is all you need.

AirBnB pro provides you with a recommendation engine and dashboard, where you can specify everything you want to consider before booking your AirBnB. You can filter by price, property type, nearest tourist attractions and much more.

## Recommendation Engine
![138058159-a777ce85-60f4-4425-a4c1-5bbe97411f78](https://user-images.githubusercontent.com/73773202/142670782-3b5ecac0-f0cc-4135-bb83-e65d4c496755.gif)

Want to stay near the nature, beside a farm ? De Baarsjes - Oud-West is the best neighbourhood for you. Be it staying near the metro or farm or art galleries our recommendation engine will find the best neighbourhood for you.

## Dashboard
![138060778-8b5c60d6-b3c4-4bf3-973f-338f4afe90c5](https://user-images.githubusercontent.com/73773202/142671057-714b2d2d-78b7-48fe-a178-64937fdb0cf0.gif)

Whether you are a foodie or an art lover our interactive dashboard will help you identify the best possible AirBnBs according to your needs. You can choose from a wide range of features like price per night, nearest attractions, distance from the city centre and so much more. We have made our dashboard user friendly so you don't have to waste much of your precious time in finding the perfect "home away from your home".

Link to Dashboard - https://rb.gy/ubs4f9

## Journey to the Centre of AirBnB Pro
* Data

For a data science project, data plays an essential role as it helps in understanding patterns, trends and help procure important information for our project through it. The data source should be reliable and provide accurate or near to perfect statistics for a good recommendation engine. For this project the data has been sourced from - http://insideairbnb.com/get-the-data.html for the Amsterdam city. Our dataset can be found here - https://rb.gy/6jclvb

* Dependencies

  * Numpy
  * Pandas
  * Seaborn
  * Sklearn
  * Matplotlib
  * Folium
  * Geopandas
  * Plotly
  * Cufflinks
  * Nltk
  * Cleantext
  * Spacy
  * Pickle
  * Wordcloud
  * Tableau
 
* Data Cleaning

Data cleaning is one of the initial steps in a data science project. It is the process of fixing or removing incorrect, corrupted, incorrectly formatted, duplicate, or missing data withing our dataset. For our project not a lot of data cleaning was required as the data used is from reliable source and did not contain any missing data. The data cleaning steps establsihed in this project include

    * Dropping neighbourhood_group - Empty Column
    * Removing "%" from host_response_rate
EDA

Exploratory Data Analysis helps us understand data more thoroughly and helps draw effcient conclusions regarding our dataset. It helps us summarise our data and helps to think about how to approach our data. Visualization plays an essential part in this step. It helps us understand data visually and helps create insights more efficiently . For this project we have used many visualization tools like folium, plotly and matlplotlib for creating beautiful and eye-catching visualizations.

  * No. of listing by neighbourhood
 ![138214510-abb8a4f5-456f-4e07-9e90-a0e311dd45ba](https://user-images.githubusercontent.com/73773202/142672778-aa8afc3f-8518-4969-a7c7-ed029ef5dd86.png)

It can be observed that most of the lisitings are situated in De Baarsjes - Oud-West

  * Visual representation of neighbourhoods on map
![138215346-b5191a86-9de9-44ba-826f-371cbac8b119](https://user-images.githubusercontent.com/73773202/142673151-8a60fb65-845c-460b-8841-e87c5f8fe81f.gif)

  * Comparison of property types of AirBnBs
 ![138215645-a1ab30c9-0a68-4539-a26f-bc3ba6555995](https://user-images.githubusercontent.com/73773202/142673300-5254f73c-54e8-4019-8573-55e5a280351f.png)
 
We can observe that apartments are the most popular type

  * Side by Side visualization of reviews and average price for a 2 persons accomodation
 ![138216163-b79bebae-405f-4b67-bb82-8fc198bdad81](https://user-images.githubusercontent.com/73773202/142673458-c85d0e67-61d0-43b3-990b-18beba915551.png)

It can be observed that Centrum-West has the highest review score and also the highest average price.

  * Visualizing average scores of different categories of reviews
 ![138217157-cff7a63f-bc9c-4069-950b-c6f9767f00d6](https://user-images.githubusercontent.com/73773202/142673544-eea68985-8048-49d6-bf20-a09d718edf5a.png)
 
* No. of listing by superhost

"Superhost" is the designation given to a host that has got good reviews consistenly by its guests.
![138217504-7a880166-583f-41bd-af7b-6c8337207eb8](https://user-images.githubusercontent.com/73773202/142673614-36aa19d8-1f0d-4000-99cf-37c6661f07eb.png)

  * No. of Listing available by date
 ![138218027-ce860ab1-2b5d-4e93-bf4b-08bcb6667862](https://user-images.githubusercontent.com/73773202/142673794-f22edac5-0d8f-405f-945f-e21e2615d5b0.png)

  * Average price of available 2 persons accommodation by date
 <img width="694" alt="138218547-07ab5d87-6f63-49c5-983c-ff4e85d6def8" src="https://user-images.githubusercontent.com/73773202/142673844-f05e829b-602e-4a12-8a01-142ee053f090.png">

* Word-Cloud creation

A Word-Cloud is the visual representation of words. The more frequently a word is used the more prominant it is. For this project word cloud has been generated using reviews.

   * Word-Cloud for reviews of all AirBnBs listed in Amsterdam
![138219210-46ef2553-d21b-48bd-aa40-f17763243320](https://user-images.githubusercontent.com/73773202/142675390-4e5f5a7d-07dc-482c-925d-7611de4e6814.png)

Words like apartment, stay, great and Amsterdam are the most prominent and hence most used in the reviews. This gives us an idea that apartments are the most popular type in Amsterdam and people have regarded it as a great place to stay.

Wordcloud can also be generated for reviews for a specific neighbourhood.

  * Word-Cloud for Gaasperdam - Driemond
 ![138219978-1d180ad1-2d73-4662-a414-e23e62ae6506](https://user-images.githubusercontent.com/73773202/142675704-af0cd9af-0cc5-4a47-8248-e89d13c19189.png)

  * Word-Cloud for Centrum-West
![138220091-7fc87fbe-5376-4a86-9a00-353e172878fb](https://user-images.githubusercontent.com/73773202/142675895-7b2b3b5e-0001-4e49-a2f5-11f55123346d.png)

* Recommendation Engine

Finally a text-based recommendation engine using NLP was built to help find the best suitable neighbourhood.

Steps taken in this process :

    * Conversion of text to word vectors
    * Training of a classifier model
    * Creating recommendation engine
 
* Dashboard

The dashboard created helps user easily identify the area and narrow-down to their favourable stay by using interactive user-interface. The dashboard conatins an interactive map and toggles to choose from , like restaurants, museums, parks, clubs and shopping places. You can also find the nearest 10 attractions, with respect to the place selected. It also allows you to choose your property type and narraw down options by inputting average price.


# *******************************************************
