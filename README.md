# PROJECT-3. Hotels EDA, Future Egeneering and Machine Learning  
[The main code is here](https://github.com/PlatArs/PROJECT-3_Hotels_ML/blob/master/Project_3_hotel-reviews-by-platars.ipynb)
[This is a Competition from Kaggle link is here](https://www.kaggle.com/competitions/sf-booking)
[And this is my code for Kaggle](https://www.kaggle.com/code/arseniiplatonov/hotel-reviews-by-platars)
### ***Problem:***
You work as a data scientist at a Booking.com company. One of the company's problems is dishonest hotels that wind up rating themselves. One of the ways to find such hotels is to build a model that predicts the rating of the hotel. If the model's predictions are very different from the actual result, then perhaps the hotel is playing dishonestly, and it is worth checking.

### ***Task:***
Make a model that predicts the rating of the hotel

### ***Dataset Description:***

hotels_train.csv - training dataset  
hotels_test.csv - a set of data for assessing the quality  
of submission.csv - a submission file in the desired format  

### ***Features:***
hotel_address - the address of the hotel  
review_date - the date when the reviewer posted the corresponding review  
average_score - the average score of the hotel calculated based on the last comment for the last year  
hotel_name - name of the hotel  
reviewer_nationality - nationality of the reviewer  
negative_review - negative review that the reviewer gave to the hotel  
review_total_negative_word_counts - the total number of words in a negative review  
positive_review - the positive review that the reviewer gave to the hotel  
review_total_positive_word_counts - the total number of words in a positive review  
reviewer_score - the rating that the reviewer gave to the hotel based on his experience  
total_number_of_reviews_reviewer_has_given - the number of reviews that reviewers have given in the past  
total_number_of_reviews - total number of valid hotel reviews  
tags - tags that the reviewer gave to the hotel  
days_since_review - the duration between the date of verification and the date of cleaning  
additional_number_of_scoring - there are also some guests who just rated the service, and did not leave a review. This number indicates how many valid estimates there are without verification  
lat - latitude of the hotel  
lng - longitude of the hotel  
