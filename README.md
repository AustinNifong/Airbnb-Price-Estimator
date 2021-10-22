# Airbnb Price Estimator

Howdyyy 🤠. This repo is a fun little personal project that I used to get my feet wet in the machine learning field. The goal of this project was to ultimately create a machine learning model to predict the daily rate for airbnb's in the greater New York area. Along the way, I also tried to incorporate many of the fundamental steps necessary for developing machine learning models such as cleaning messy data, creating new features, and tuning hyperparameters during cross-validation. 

## The Data
* I used data from http://insideairbnb.com/ which offers airbnb datasets that contain every airbnb listing categorized by city and date. For this project, I simply used 1 dataset from August 4, 2021 for the NYC area, although this repo could certainly be used for any of the other datasets. This particular dataset contains 36724 samples and 74 columns.

* Here's a snippet of what we're working with:

<img width="1064" alt="Screen Shot 2021-10-21 at 10 39 52 PM" src="https://user-images.githubusercontent.com/20541568/138384472-763d07f9-4ef6-4e9a-8225-cf922a584243.png">

* Upon further exploration with Pandas, we have some fun facts:
  * Median price: $108
  * <a href="https://www.airbnb.com/rooms/13925864?source_impression_id=p3_1634871163_ljIRjknK7Sxq5Fjb" target="_blank"> Most expensive </a>: $10,000 (surely a listing mistake?)
  * <a href="https://www.airbnb.com/rooms/34071681?source_impression_id=p3_1634871370_vf7ADDNtV0fjwGBF" target="_blank">Most reviewed</a>: 1009 reviews
  * <a href="https://www.airbnb.com/rooms/45910?source_impression_id=p3_1634873288_gLh%2BUToQlso1asrH" target="_blank">Most accomodating</a>: 16 people
  * <a href="https://www.airbnb.com/rooms/43298710?source_impression_id=p3_1634872166_82xSpr0y%2FA5p8Yi1" target="_blank">Person with most listings</a> : June from June Homes who has >= 335 listings 🤑

* One major future improvement is to use multiple datasets of different dates in order to predict airbnb prices throughout the year.
