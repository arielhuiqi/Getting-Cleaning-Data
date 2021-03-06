## Data Transformation 

Done by `run_analysis.R` script.

1. Read the `Activity files`, `Subject files` and `Features files`.
2. Merge the datasets by concatenating the data tables by rows and merge columns to get the data frame Data for all data.
3. Calculate the mean and sd.
4. Subset the data frame Data by seleted names of Features.

## Variable Descriptions

'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.

The set of variables that were estimated from these signals are:
- mean: Mean value
- std: Standard deviation

## Data Columns

1.  subject
2.	activity
3.	timeimeBodyAccelerometerelerometer.mean...X
4.	timeimeBodyAccelerometerelerometer.mean...Y
5.	timeimeBodyAccelerometerelerometer.mean...Z
6.	timeimeBodyAccelerometerelerometer.std...X
7.	timeimeBodyAccelerometerelerometer.std...Y
8.	timeimeBodyAccelerometerelerometer.std...Z
9.	timeimeGravityAccelerometerelerometer.mean...X
10.	timeimeGravityAccelerometerelerometer.mean...Y
11.	timeimeGravityAccelerometerelerometer.mean...Z
12.	timeimeGravityAccelerometerelerometer.std...X
13.	timeimeGravityAccelerometerelerometer.std...Y
14.	timeimeGravityAccelerometerelerometer.std...Z
15.	timeimeBodyAccelerometerelerometerJerk.mean...X
16.	timeimeBodyAccelerometerelerometerJerk.mean...Y
17.	timeimeBodyAccelerometerelerometerJerk.mean...Z
18.	timeimeBodyAccelerometerelerometerJerk.std...X
19.	timeimeBodyAccelerometerelerometerJerk.std...Y
20.	timeimeBodyAccelerometerelerometerJerk.std...Z
21.	timeimeBodyGyroscopescope.mean...X
22.	timeimeBodyGyroscopescope.mean...Y
23.	timeimeBodyGyroscopescope.mean...Z
24.	timeimeBodyGyroscopescope.std...X
25.	timeimeBodyGyroscopescope.std...Y
26.	timeimeBodyGyroscopescope.std...Z
27.	timeimeBodyGyroscopescopeJerk.mean...X
28.	timeimeBodyGyroscopescopeJerk.mean...Y
29.	timeimeBodyGyroscopescopeJerk.mean...Z
30.	timeimeBodyGyroscopescopeJerk.std...X
31.	timeimeBodyGyroscopescopeJerk.std...Y
32.	timeimeBodyGyroscopescopeJerk.std...Z
33.	timeimeBodyAccelerometerelerometerMagnitudenitude.mean..
34.	timeimeBodyAccelerometerelerometerMagnitudenitude.std..
35.	timeimeGravityAccelerometerelerometerMagnitudenitude.mean..
36.	timeimeGravityAccelerometerelerometerMagnitudenitude.std..
37.	timeimeBodyAccelerometerelerometerJerkMagnitudenitude.mean..
38.	timeimeBodyAccelerometerelerometerJerkMagnitudenitude.std..
39.	timeimeBodyGyroscopescopeMagnitudenitude.mean..
40.	timeimeBodyGyroscopescopeMagnitudenitude.std..
41.	timeimeBodyGyroscopescopeJerkMagnitudenitude.mean..
42.	timeimeBodyGyroscopescopeJerkMagnitudenitude.std..
43.	frequencyrequencyBodyAccelerometerelerometer.mean...X
44.	frequencyrequencyBodyAccelerometerelerometer.mean...Y
45.	frequencyrequencyBodyAccelerometerelerometer.mean...Z
46.	frequencyrequencyBodyAccelerometerelerometer.std...X
47.	frequencyrequencyBodyAccelerometerelerometer.std...Y
48.	frequencyrequencyBodyAccelerometerelerometer.std...Z
49.	frequencyrequencyBodyAccelerometerelerometerJerk.mean...X
50.	frequencyrequencyBodyAccelerometerelerometerJerk.mean...Y
51.	frequencyrequencyBodyAccelerometerelerometerJerk.mean...Z
52.	frequencyrequencyBodyAccelerometerelerometerJerk.std...X
53.	frequencyrequencyBodyAccelerometerelerometerJerk.std...Y
54.	frequencyrequencyBodyAccelerometerelerometerJerk.std...Z
55.	frequencyrequencyBodyGyroscopescope.mean...X
56.	frequencyrequencyBodyGyroscopescope.mean...Y
57.	frequencyrequencyBodyGyroscopescope.mean...Z
58.	frequencyrequencyBodyGyroscopescope.std...X
59.	frequencyrequencyBodyGyroscopescope.std...Y
60.	frequencyrequencyBodyGyroscopescope.std...Z
61.	frequencyrequencyBodyAccelerometerelerometerMagnitudenitude.mean..
62.	frequencyrequencyBodyAccelerometerelerometerMagnitudenitude.std..
63.	frequencyrequencyBodyAccelerometerelerometerJerkMagnitudenitude.mean..
64.	frequencyrequencyBodyAccelerometerelerometerJerkMagnitudenitude.std..
65.	frequencyrequencyBodyGyroscopescopeMagnitudenitude.mean..
66.	frequencyrequencyBodyGyroscopescopeMagnitudenitude.std..
67.	frequencyrequencyBodyGyroscopescopeJerkMagnitudenitude.mean..
68.	frequencyrequencyBodyGyroscopescopeJerkMagnitudenitude.std..
