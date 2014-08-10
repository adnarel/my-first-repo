## Getting and Cleaning Data
### getdata-006
### Course Project
###
###
#### CodeBook for "tidy" dataset 
#### "merged_subset_averages.csv"
<br><br>
There are a total of 81 columns and 180 rows in this dataset.
<br><br>
Each row is a summary of smartphone motion data
for one volunteer subject engaged in a certain activity.
<br><br>
Each column represents a variable.  The contents of
the 81 columns are summarized below.
<br><br>
columns 3-42 are extracted and averaged time domain signal data from the raw datasets:
   variable names begin with "t" 

columns 43-81 are extracted and averaged frequency domain signal data from the raw datasets:
   variable names begin with "f"
<br><br>
The raw data was normalized and bounded within [-1,1], so the signal data in columns 3-81 are unitless.
<br><br>


####Abbreviations:

std.dev. = Standard Deviation<br>
3D       = 3-dimensional<br>
grav.    = gravitational<br>

<br><br>

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3



####Column Variables Summary:
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| Column Number | Variable Name                       | Variable Type      | Column Number in raw data |  Description                                                                       |
+===============+=====================================+====================+===========================+====================================================================================+
| 1             | activity                            | character          | N/A                       | The 6 different activities                                                         |
|               |                                     |                    |                           | performed by the study subjects                                                    |
|               |                                     |                    |                           | while wearing a smartphone on their waist                                          |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 2             | subject                             | integer            | N/A                       | The 30 volunteer people who                                                        |
|               |                                     |                    |                           | performed activities while wearing                                                 |
|               |                                     |                    |                           | a smartphone on their waist.                                                       |
|               |                                     |                    |                           | Ages ranged from 19-48                                                             |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 3             | tBodyAcc-mean()-X                   | floaing point      | 1                         | Average value of mean body acceleration - X axis,                                  |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 4             | tBodyAcc-mean()-Y                   | floaing point      | 2                         | Average value of mean body acceleration - Y axis,                                  |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 5             | tBodyAcc-mean()-Z                   | floaing point      | 3                         | Average value of mean body acceleration - Z axis,                                  |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 6             | tBodyAcc-std()-X                    | floaing point      | 4                         | Average value of std.dev. of body acceleration - X axis,                           |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 7             | tBodyAcc-std()-Y                    | floaing point      | 5                         | Average value of std.dev. of body acceleration - Y axis,                           |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 8             | tBodyAcc-std()-Z                    | floaing point      | 6                         | Average value of std.dev. of body acceleration - Z axis,                           |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 9             | tGravityAcc-mean()-X                | floaing point      | 41                        | Average value of mean grav. acceleration - X axis,                                 |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 10            | tGravityAcc-mean()-Y                | floaing point      | 42                        | Average value of mean grav. acceleration - Y axis,                                 |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 11            | tGravityAcc-mean()-Z                | floaing point      | 43                        | Average value of mean grav. acceleration - Z axis,                                 |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 12            | tGravityAcc-std()-X                 | floaing point      | 44                        | Average value of std.dev. of grav. acceleration - X axis,                          |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 13            | tGravityAcc-std()-Y                 | floaing point      | 45                        | Average value of std.dev. of grav. acceleration - Y axis,                          |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 14            | tGravityAcc-std()-Z                 | floaing point      | 46                        | Average value of std.dev. of grav. acceleration - Z axis,                          |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 15            | tBodyAccJerk-mean()-X               | floaing point      | 81                        | Average value of mean body jerk acceleration - X axis,                             |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 16            | tBodyAccJerk-mean()-Y               | floaing point      | 82                        | Average value of mean body jerk acceleration - Y axis,                             |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 17            | tBodyAccJerk-mean()-Z               | floaing point      | 83                        | Average value of mean body jerk acceleration - Z axis,                             |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 18            | tBodyAccJerk-std()-X                | floaing point      | 84                        | Average value of std.dev. of body jerk acceleration - X axis,                      |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 19            | tBodyAccJerk-std()-Y                | floaing point      | 85                        | Average value of std.dev. of body jerk acceleration - Y axis,                      |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 20            | tBodyAccJerk-std()-Z                | floaing point      | 86                        | Average value of std.dev. of body jerk acceleration - Z axis,                      |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 21            | tBodyGyro-mean()-X                  | floaing point      | 121                       | Average value of mean body angular velocity - X axis,                              |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 22            | tBodyGyro-mean()-Y                  | floaing point      | 122                       | Average value of mean body angular velocity - Y axis,                              |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 23            | tBodyGyro-mean()-Z                  | floaing point      | 123                       | Average value of mean body angular velocity - Z axis,                              |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 24            | tBodyGyro-std()-X                   | floaing point      | 124                       | Average value of std.dev. of body angular velocity - X axis,                       |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 25            | tBodyGyro-std()-Y                   | floaing point      | 125                       | Average value of std.dev. of body angular velocity - Y axis,                       |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 26            | tBodyGyro-std()-Z                   | floaing point      | 126                       | Average value of std.dev. of body angular velocity - Z axis,                       |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 27            | tBodyGyroJerk-mean()-X              | floaing point      | 161                       | Average value of mean body jerk angular velocity - X axis,                         |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 28            | tBodyGyroJerk-mean()-Y              | floaing point      | 162                       | Average value of mean body jerk angular velocity - Y axis,                         |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 29            | tBodyGyroJerk-mean()-Z              | floaing point      | 163                       | Average value of mean body jerk angular velocity - Z axis,                         |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 30            | tBodyGyroJerk-std()-X               | floaing point      | 164                       | Average value of std.dev. of body jerk angular velocity - X axis,                  |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 31            | tBodyGyroJerk-std()-Y               | floaing point      | 165                       | Average value of std.dev. of body jerk angular velocity - Y axis,                  |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 32            | tBodyGyroJerk-std()-Z               | floaing point      | 166                       | Average value of std.dev. of body jerk angular velocity - Z axis,                  |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 33            | tBodyAccMag-mean()                  | floaing point      | 201                       | Average value of mean body acceleration 3D signal magnitude,                       |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 34            | tBodyAccMag-std()                   | floaing point      | 202                       | Average value of std.dev. of body acceleration 3D signal magnitude,                |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 35            | tGravityAccMag-mean()               | floaing point      | 214                       | Average value of mean grav. acceleration 3D signal magnitude,                      |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 36            | tGravityAccMag-std()                | floaing point      | 215                       | Average value of std.dev. of grav. acceleration 3D signal magnitude,               |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 37            | tBodyAccJerkMag-mean()              | floaing point      | 227                       | Average value of mean body jerk acceleration 3D signal magnitude,                  |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 38            | tBodyAccJerkMag-std()               | floaing point      | 228                       | Average value of std.dev. of body jerk acceleration 3D signal magnitude,           |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 39            | tBodyGyroMag-mean()                 | floaing point      | 240                       | Average value of mean body angular velocity 3D signal magnitude,                   |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 40            | tBodyGyroMag-std()                  | floaing point      | 241                       | Average value of std.dev. of body angular velocity 3D signal magnitude,            |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 41            | tBodyGyroJerkMag-mean()             | floaing point      | 253                       | Average value of mean body jerk angular velocity 3D signal magnitude,              |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 42            | tBodyGyroJerkMag-std()              | floaing point      | 254                       | Average value of std.dev. of body jerk angular velocity 3D signal magnitude,       |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -time-domain signal                                                                |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 43            | fBodyAcc-mean()-X                   | floaing point      | 266                       | Average value of mean body acceleration - X axis,                                  |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 44            | fBodyAcc-mean()-Y                   | floaing point      | 267                       | Average value of mean body acceleration - Y axis,                                  |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 45            | fBodyAcc-mean()-Z                   | floaing point      | 268                       | Average value of mean body acceleration - Z axis,                                  |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 46            | fBodyAcc-std()-X                    | floaing point      | 269                       | Average value of std.dev. of body acceleration - X axis,                           |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 47            | fBodyAcc-std()-Y                    | floaing point      | 270                       | Average value of std.dev. of body acceleration - Y axis,                           |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 48            | fBodyAcc-std()-Z                    | floaing point      | 271                       | Average value of std.dev. of body acceleration - Z axis,                           |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 49            | fBodyAcc-meanFreq()-X               | floaing point      | 294                       | Average value of mean frequency of body acceleration - X axis,                     |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 50            | fBodyAcc-meanFreq()-Y               | floaing point      | 295                       | Average value of mean frequency of body acceleration - Y axis,                     |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 51            | fBodyAcc-meanFreq()-Z               | floaing point      | 296                       | Average value of mean frequency of body acceleration - Z axis,                     |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 52            | fBodyAccJerk-mean()-X               | floaing point      | 345                       | Average value of mean body jerk acceleration - X axis,                             |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 53            | fBodyAccJerk-mean()-Y               | floaing point      | 346                       | Average value of mean body jerk acceleration - Y axis,                             |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 54            | fBodyAccJerk-mean()-Z               | floaing point      | 347                       | Average value of mean body jerk acceleration - Z axis,                             |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 55            | fBodyAccJerk-std()-X                | floaing point      | 348                       | Average value of std.dev. of body jerk acceleration - X axis,                      |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 56            | fBodyAccJerk-std()-Y                | floaing point      | 349                       | Average value of std.dev. of body jerk acceleration - Y axis,                      |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 57            | fBodyAccJerk-std()-Z                | floaing point      | 350                       | Average value of std.dev. of body jerk acceleration - Z axis,                      |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 58            | fBodyAccJerk-meanFreq()-X           | floaing point      | 373                       | Average value of mean frequency of body jerk acceleration - X axis,                |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 59            | fBodyAccJerk-meanFreq()-Y           | floaing point      | 374                       | Average value of mean frequency of body jerk acceleration - Y axis,                |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 60            | fBodyAccJerk-meanFreq()-Z           | floaing point      | 375                       | Average value of mean frequency of body jerk acceleration - Z axis,                |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 61            | fBodyGyro-mean()-X                  | floaing point      | 424                       | Average value of mean body angular velocity - X axis,                              |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 62            | fBodyGyro-mean()-Y                  | floaing point      | 425                       | Average value of mean body angular velocity - Y axis,                              |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 63            | fBodyGyro-mean()-Z                  | floaing point      | 426                       | Average value of mean body angular velocity - Z axis,                              |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 64            | fBodyGyro-std()-X                   | floaing point      | 427                       | Average value of std.dev. of body angular velocity - X axis,                       |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 65            | fBodyGyro-std()-Y                   | floaing point      | 428                       | Average value of std.dev. of body angular velocity - Y axis,                       |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 66            | fBodyGyro-std()-Z                   | floaing point      | 429                       | Average value of std.dev. of body angular velocity - Z axis,                       |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 67            | fBodyGyro-meanFreq()-X              | floaing point      | 452                       | Average value of mean frequency of body angular velocity - X axis,                 |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 68            | fBodyGyro-meanFreq()-Y              | floaing point      | 453                       | Average value of mean frequency of body angular velocity - Y axis,                 |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 69            | fBodyGyro-meanFreq()-Z              | floaing point      | 454                       | Average value of mean frequency of body angular velocity - Z axis,                 |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 70            | fBodyAccMag-mean()                  | floaing point      | 503                       | Average value of mean body acceleration 3D signal magnitude,                       |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 71            | fBodyAccMag-std()                   | floaing point      | 504                       | Average value of std.dev. of body acceleration 3D signal magnitude,                |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 72            | fBodyAccMag-meanFreq()              | floaing point      | 513                       | Average value of mean frequency of body acceleration 3D signal magnitude,          |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 73            | fBodyBodyAccJerkMag-mean()          | floaing point      | 516                       | Average value of mean body jerk acceleration 3D signal magnitude,                  |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 74            | fBodyBodyAccJerkMag-std()           | floaing point      | 517                       | Average value of std.dev. of body jerk acceleration 3D signal magnitude,           |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 75            | fBodyBodyAccJerkMag-meanFreq()      | floaing point      | 526                       | Average value of mean frequency of body jerk acceleration 3D signal magnitude,     |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 76            | fBodyBodyGyroMag-mean()             | floaing point      | 529                       | Average value of mean body angular velocity 3D signal magnitude,                   |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 77            | fBodyBodyGyroMag-std()              | floaing point      | 530                       | Average value of std.dev. of body angular velocity 3D signal magnitude,            |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 78            | fBodyBodyGyroMag-meanFreq()         | floaing point      | 539                       | Average value of mean frequency of body angular velocity 3D signal magnitude,      |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 79            | fBodyBodyGyroJerkMag-mean()         | floaing point      | 542                       | Average value of mean body jerk angular velocity 3D signal magnitude,              |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 80            | fBodyBodyGyroJerkMag-std()          | floaing point      | 543                       | Average value of std.dev. of body jerk angular velocity 3D signal magnitude,       |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+
| 81            | fBodyBodyGyroJerkMag-meanFreq()     | floaing point      | 552                       | Average value of mean frequency of body jerk angular velocity 3D signal magnitude, |
|               |                                     | decimal            |                           | averaged for each subject and activity                                             |
|               |                                     |                    |                           | -frequency-domain signal                                                           |
+---------------+-------------------------------------+--------------------+---------------------------+------------------------------------------------------------------------------------+

