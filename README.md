# Power Predictor: Machine Learning Powerlifter

#### [Google Collab File](https://github.com/MarkMinia/Project7/blob/main/Powerlifting_Machine_Learning_Final_KG_Total.ipynb)

##### After attempting the Titanic competition on Kaggle, I decided to run through the process, again, but on the topic of powerlifting because it's my primary hobby at this time.

##### My research question is, by using a lifter's basic profile and opening attempt selections, can a machine learning model forecast a lifter's final kg total before that person steps on the platform? 

##### By basic profile, I mean things like age, weight, gender etc.

##### Powerlifting is a sport in which competitors compete to lift the most weight in their specific weightclass. There are three lifts: The squat, bench, and deadlift. You get 3 attempts in each and your best squat, bench, and deadlift numbers are added together to get the final total. So, without looking at 2nd and 3rd attempts, I wanted to see if the opening attempts can be used to predict the final outcome because that is something lifters need to provide to the staff before the competition even begins. Personally, It would also be interesting to see how someone could potentially place in the standings, like 1st, 2nd, or 3rd place.

##### The LGBMR Regressor provided the best results, but not many models were used due to computer issues as Collab kept crashing from runtime errors.

##### From personal experience, I had a feeling this was going to be difficult to predict for a couple reasons, but I was still curious on the results. Some lifters use calculated percentages for picking attempts, some use gut instincts, so that can be a challenge for the model. And if a lifter fails a lift, they often re-attempt it, so they give up the chance to go for a higher total than initially planned. 

##### There's a website called OpenPowerlifting.com that is updated real-time with meets around the world, but the file size was too large. I found one on Kaggle that was half the size, but was still too large for Collab, so I had to upload it using the Kaggle API.

##### I chose to focus on........ 

