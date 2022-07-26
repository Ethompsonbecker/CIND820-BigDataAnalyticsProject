# Results Table 

The table below shows the average values of the evaluation metrics from all 3 regression analysis methods. The values were calculating by taking the sum of the measure for each trial and dividing that by the total number of trials.   

The models denoted with an A represent the analyses preformed with the inclusion of the independent variable PM10.   
The models denoted with a B represent the analyses preformed without the independedent variable PM10.   

The models with a 1 include the weathered data where the models with a 2 exclude the weather data. 


|Model|Adjusted R^2| MAE | RMSE  |
|-------|-------------|------|------|
|MLR-A-1| 76.7239727|0.024300273|0.036403545 | 
|MLR-A-2|78.0731545|0.027172182|0.041858545|
|MLR-B-1|55.0984909|0.035442364|0.052039364|
|MLR-B-2|57.5925455|0.037962636|0.056407909|
|------|-----------|---------|------|
|RR-A-1|71.5528636|0.028913818|0.041352727|
|RR-A-2|70.9870182|0.027715364|0.042379|
|RR-B-1|55.0784455|0.036147818|0.051931545|
|RR-B-2|53.7416636|0.036181545|0.053725455|
|------|---------|---------|----------|
|RFR-A-1|84.2197818|0.018352|0.029506636|
|RFR-A-2|84.1840727|0.01900.091|0.030606455|
|RFR-B-1|49.0492182|0.033674273|0.052331545|
|RFR-B-2|52.22196545|0.035859182|0.054932364|


The Ranking of the Models was calculated by assigning each evaluation measure a rank and totaling the ranks of each model. The output is displayed below

|Rank|  1| 2| 3| 4| 5| 6| 7| 8| 9|10|11|12|
|---|-|--|--|--|--|--|--|--|--|--|--|--|
|Model| RFR-A-1|RFR-A-2|RR-A-1|MLR-A-1|MLR-A-2|RR-A_2|MLR-B-1|RR-B-1|RFR-B-1|RR-B-2|RFR-B-2|MLR-B-2|

As predicted the models that included the variable PM10 had much better fits than those without it. 

|Feature	|RFR-A-1|	RR-A-1	|MLR-A-1|	RFR-A-2|	RR-A-2	|MLR-A-2|	Result|
|--------|-----|----------|--------|---------|---------|-------|--------|
|PM10	|1	|1|	1|	X|	X|	X|	 |
|SO2|	6|	6	|6|	7|	4|	4|	|
|NO2|	5|	8|	8|	3|	2|	2|	|
|CO|	2|	2|	2|	1|	1|	1|	|
|O3|	8|	5|	5|	5|	6|	6|	|
|TEMP|	4|	4(-)|	4(-)|	6|	5(-)|	5 (-)| |	
|PRES|	7|	7	|7	|4	|8	|8	|   |
|DEWP|	3|	3|	3|	2|	3|	3|	| 
|WSPM|	9|	9(-)|	9(-)|	8|	7|	7|   |	

The negatives indicate a negative coefficient. 
