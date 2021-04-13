# car_price_competition

This project was done as part of a “Machine learning” course at my university. During the course there was a Kaggle competition among all the course attenders. (link to the competition - https://www.kaggle.com/c/gsom-21sm1-ml-homework-1)
As a results, our team took the second place, losing only to the teacher.

In this project I used the following techniques:
1)	Feature extraction – a low of new features was added and tested
2)	Preprocessing – taking logarithms, filling nans etc.
3)	About nans – two variables (taxes and mpg) had a lot of nans, but they were crucial for the regression. That’s why I decided to build additional models to predict their nans first
4)	Model for prediction – Random Forest Regressor
5)	Tuned hyperparameters using GridSearch

TASK

A local car workshop asked for help.

One of their services is preparing used cars for sale: washing, polishing, dry cleaning the interior, fixing small but noticeable issues. Depending on the car (and the amount of money the owner is expecting to get), the number of actions may vary. At least, the workshop owner is absolutely sure that prettifying the Mercedes-Benz SL can cost much more than cleaning up the Ford Focus.

Therefore the workshop's revenue highly depends on how precisely the workshop administrator detected the customer's willingness to pay. The workshop owner thinks that their workshop needs the system that quickly guesses the used car price from the car's basic characteristics. Such a system on the workshop administrator's computer will help administrators to evaluate the customer's willingness to pay much more precisely -- and will even help car owners.

The Russian start-up founded from this idea: https://maxposter.ru
