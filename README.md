# Shiran Yuan's STATS 201 Repository
This is Shiran Yuan's repository for the course STATS 201.

## Table of Contents
* [Bio](#bio)
* [Project Information](#project-information)
* [Data](#data)
* [Code](#code)
* [Spotlights](#spotlights)
* [Conclusions](#conclusions)

## Bio
![Shiran](https://user-images.githubusercontent.com/105504535/213655331-9881b742-241d-48af-b3c3-27fdb4d8092d.jpeg)

Shiran Yuan was born on September 2007. He dropped out of primary school during second grade in 2016 (age 8) after receiving a scholarship, and began self-studying since then. 

In 2017 (age 9) he received IELTS band 7. 

In 2018 (age 10), he completed the Shing-Tung Yau Mathcamp course at Tsinghua University, received Honor Roll of Distinction in the Second Round of the Mathematics League Competition (Grades 9-12 Track), earned High Honors in the Johns Hopkins Center for Talented Youth's Talent Search Program, received a TOEFL score of 109, and was awarded the AP Scholar with Honor Award from the CollegeBoard. 

In 2019 (age 11), he received the AP Scholar with Distinction Award from the CollegeBoard and a DELF B2 (French language) certificate.

In 2020 (age 12), he completed the Hsue-Shen Tsien Excellence in Engineering Program Summer Camp course at Tsinghua University.

In 2021 (age 13), he was admitted to DKU with a full scholarship, and received the top prize at X-Institute (an academic research institution founded by Tsinghua University) Summer Camp.

In 2022 (age 14), he became an X-Institute Scholar, and received the Silver Medal in the iGEM Competition.

His current intended major is Applied Mathematics and Computational Sciences (Computer Science Track).

## Project Information
In this problem set, I am going to explore tweets about data privacy/security in blockchain over the past 10 years (Jan 1st 2013 to Dec 31st 2022). The following are the research questions:
* Part I (Explanation): What are the main keywords and topics of tweets about data privacy/security in blockchain over the past 10 years?
* Part II (Prediction): Is data privacy/security in blockchain projected to become increasingly or decreasingly popular as a topic on Twitter in 2023?
The project contains a total number of 4 data files, 7 code files, and 6 spotlight figures. All data and code were produced independently by the author.

## Data
All data files are stored within the `data` directory.
* `Explanation_Data.txt`: Contains the raw content of all queried tweets.
* `PS2_Data.txt`: Contains the number of queried tweets for each day from Jan 1st 2013 to Dec 31st 2022. Days without queried tweets are not shown.
* `Monthly_Predict.txt`: Contains predictions of the number of queried tweets by months according to the prediction model.
* `Daily_Predict.txt`: Contains predictions of the number of queried tweets by days according to the prediction model.

## Code
All code files are stored within the `code` directory.
* `PS2_Explanation_Query.ipynb`: Queries and processes the raw content of all queried tweets. Produces the data file `Explanation_Data.txt`.
* `PS2_Explanation_Analyze.ipynb`: Analyzes `Explanation_Data.txt`. Produces the spotlight figure `spotlight6.png`.
* `PS2_Query_Data.ipynb`: Queries tweets and records their dates. Produces the data file `PS2_Data.txt`.
* `PS2_Process_Data.ipynb`: Processes and visualizes `PS2_Data.txt`. Produces the spotlight figures `spotlight1.png` and `spotlight2.png`.
* `PS2_Matlab_Models/Daily_Model.mat`: A Exponential Gaussian Process Regression model trained by Regression Learner from MATLAB based on daily data.
* `PS2_Matlab_Models/Monthly_Model.mat`: A Exponential Gaussian Process Regression model trained by Regression Learner from MATLAB based on monthly data.
* `PS2_Analyze_Data.ipynb`: Visualizes the predictions from `Monthly_Predict.txt` and `Daily_Predict.txt`. Produces the spotlight figures `spotlight4.png` and `spotlight5.png`.

## Spotlights
* `spotlight1.png`: The number of queried tweets by months.

![spotlight1](https://user-images.githubusercontent.com/105504535/219619566-fc0132f5-e153-44c5-89b0-bede3d9fc77b.png)

* `spotlight2.png`: The number of queried tweets by days, and the smoothed version of this data smoothed by weekly averages.
![spotlight2](https://user-images.githubusercontent.com/105504535/219619587-8bce2247-9313-4e19-8a56-7ae0e0b389ee.png)

* `spotlight3.png`: An intuitive display of the relationship of the queried data with the DAO hack incident and its subsequent SEC ruling.
![spotlight3](https://user-images.githubusercontent.com/105504535/219619609-fdb3a6ec-7be7-4362-adbe-d6e0fe047f23.png)

* `spotlight4.png`: Prediction of future trends of the number of queried tweets by months in 2023.
![spotlight4](https://user-images.githubusercontent.com/105504535/219619641-a40ecdfe-a574-463a-ae56-3c048d549032.png)

* `spotlight5.png`: Prediction of future trends of the number of queried tweets by days in 2023.
![spotlight5](https://user-images.githubusercontent.com/105504535/219619896-09ecb443-f557-435e-8166-96ea4301c888.png)

* `spotlight6.png`: A word cloud of the keywords of the queried tweets.
![spotlight6](https://user-images.githubusercontent.com/105504535/219619980-dc9f4924-09d3-4b38-b3e0-6987ecd3d3e6.png)

## Conclusions
The following conclusions are reached from this project.
* The main keywords of tweets about data privacy/security in blockchain over the past 10 years include: new technologies (e.g. artificial intelligence, cryptocurrencies, big data), major blockchain platforms (e.g. Bitcoin, Ethereum), major security threats (e.g. ransomware, data breach), and related fields of applications (e.g. healthcare, biometrics, cryptography).
* The popularity of data privacy/security in blockchain as a Twitter topic is projected to decrease over 2023, unless an unpredictable incident similar to the DAO hack and its aftermath occurs in the near future.
* The SEC ruling of the DAO hack incident seems to have had more impact on the popularity of the topic of data privacy/security in blockchain than the incident itself. (An unexpected discovery not corresponding to predetermined research questions)
