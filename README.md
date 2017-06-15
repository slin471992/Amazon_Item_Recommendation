This project provides better item recommendation (Books, Music Instruments, etc) by using Amazon's dataset.

Dataset used: Amazon's Dataset "Music Instruments (Ratings only)". http://jmcauley.ucsd.edu/data/amazon/.

Database used: Mongodb.

Libraries used: bson-3.4.1, java-json, mongo-java-driver-3.4.1, mongodb-driver-core-3.4.1.

To run: 

	1. First run Purify.java to purify and import data into the database

	2. Run Prediction.java to get item recommendations. 