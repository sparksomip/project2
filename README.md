# Project 2
<h3>High Water Project</h3>

You are provided with a dataset concerning high tides in Venice. These data are used by the “Centro Previsioni e Segnalazioni Maree” to produce forecasts of high tide. The data comprises information gathered from a number of Venetian meteorological station. Each station tracks different kinds of information, depending on the sensors that have been installed. The training dataset consists of 1000 measurements (taken at different times) of input variables that can be used to predict high tide. Note that the observations are not ordered in time. For these observations you know whether the phenomenon of high tide was observed exactly 6 hours following the observation (y = 2) or not (y = 1). For the additional 866 measurements in the test set, you only have the inputs. Your goal is to predict y for the held–out 866 unit in the test set.

<h4>Input Variables</h4>  
There are 37 input variables, most of which are self explanatory, consisting of measurements from the different stations of the quantities below.<br> 
1. Astronomical_Tide+6, the astronomical tide level exactly six hours following the time of the observation (see note on tide below)<br>
2. Average_Tide_Level<br>
3. Average_Wind_Direction, measured in degrees<br>
4. Average_Wind_Speed<br>
5. Max_Wind_Speed<br>
6. Humidity<br>
7. Solar_Radiation<br>
8. Air_Temperature<br>
9. Water_Temperature<br>
10. Pressure<br>
11. Significant_Wave_Height, the average height of the 33% highest waves<br>
12. Max_Wave_Height<br>
13. Rain_Level<br>

<h4>(Links here!)</h4>  
- Problem Description: [https://github.com/sparksomip/project1/blob/main/Problem-Details.pdf]<br>
- Train Data Set: [https://github.com/sparksomip/project1/blob/main/train.csv]<br>
- Test Data Set: [https://github.com/sparksomip/project1/blob/main/test.csv]<br>
- Weight Calculation Method: [https://github.com/sparksomip/project1/blob/main/test.csv]<br>
- Result Submitted: [https://github.com/sparksomip/project1/blob/main/FInal%20Submission%20of%20Spam%20Detection_Forecast.txt]<br>
