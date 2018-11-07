## CODEBOOK

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain. See 'features_info.txt' for more details. 

Please read about the experiment at

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

for more information.

For each record it is provided:
======================================

- Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.
- Triaxial Angular velocity from the gyroscope. 
- A 561-feature vector with time and frequency domain variables. 
- Its activity label. 
- An identifier of the subject who carried out the experiment.

The code run_analysis.R produces the following files:
=====================================================

tidy_data.txt
tidy_data_means.txt


Notes: 
======
- Features are normalized and bounded within [-1,1].
- Each feature vector is a row on the text file.

For more information about this dataset contact: activityrecognition@smartlab.ws

License:
========
Raw Data is downloaded by obtaining a zipped file from 

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Use of this dataset in publications must be acknowledged by referencing the following publication [1] 

[1] Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. Human Activity Recognition on Smartphones using a Multiclass Hardware-Friendly Support Vector Machine. International Workshop of Ambient Assisted Living (IWAAL 2012). Vitoria-Gasteiz, Spain. Dec 2012

This dataset is distributed AS-IS and no responsibility implied or explicit can be addressed to the authors or their institutions for its use or misuse. Any commercial use is prohibited.

Jorge L. Reyes-Ortiz, Alessandro Ghio, Luca Oneto, Davide Anguita. November 2012.

# Basic variables

All following variables are ranked in order. 

There were 30 subjects, humen. The first variable is "subject".

Each subject performs one activity at the time. The second variable is "activity" and has values

WALKING
WALKING_UPSTAIRS
WALKING_DOWNSTAIRS
SITTING
STANDING
LAYING

# Sensor variables
Following variables were measured from the sensors in the experiment, their names are descriptive.

timeDomain-Body-Accelerometer-mean-X
timeDomain-Body-Accelerometer-mean-Y
timeDomain-Body-Accelerometer-mean-Z
timeDomain-Body-Accelerometer-std-X
timeDomain-Body-Accelerometer-std-Y
timeDomain-Body-Accelerometer-std-Z
timeDomain-Gravity-Accelerometer-mean-X
timeDomain-Gravity-Accelerometer-mean-Y
timeDomain-Gravity-Accelerometer-mean-Z
timeDomain-Gravity-Accelerometer-std-X
timeDomain-Gravity-Accelerometer-std-Y
timeDomain-Gravity-Accelerometer-std-Z
timeDomain-Body-Accelerometer-Jerk-mean-X
timeDomain-Body-Accelerometer-Jerk-mean-Y
timeDomain-Body-Accelerometer-Jerk-mean-Z
timeDomain-Body-Accelerometer-Jerk-std-X
timeDomain-Body-Accelerometer-Jerk-std-Y
timeDomain-Body-Accelerometer-Jerk-std-Z
timeDomain-Body-Gyroscope-mean-X
timeDomain-Body-Gyroscope-mean-Y
timeDomain-Body-Gyroscope-mean-Z
timeDomain-Body-Gyroscope-std-X
timeDomain-Body-Gyroscope-std-Y
timeDomain-Body-Gyroscope-std-Z
timeDomain-Body-Gyroscope-Jerk-mean-X
timeDomain-Body-Gyroscope-Jerk-mean-Y
timeDomain-Body-Gyroscope-Jerk-mean-Z
timeDomain-Body-Gyroscope-Jerk-std-X
timeDomain-Body-Gyroscope-Jerk-std-Y
timeDomain-Body-Gyroscope-Jerk-std-Z
timeDomain-Body-Accelerometer-Magnitude-mean
timeDomain-Body-Accelerometer-Magnitude-std
timeDomain-Gravity-Accelerometer-Magnitude-mean
timeDomain-Gravity-Accelerometer-Magnitude-std
timeDomain-Body-Accelerometer-Jerk-Magnitude-mean
timeDomain-Body-Accelerometer-Jerk-Magnitude-std
timeDomain-Body-Gyroscope-Magnitude-mean
timeDomain-Body-Gyroscope-Magnitude-std
timeDomain-Body-Gyroscope-Jerk-Magnitude-mean
timeDomain-Body-Gyroscope-Jerk-Magnitude-std
frequencyDomain-Body-Accelerometer-mean-X
frequencyDomain-Body-Accelerometer-mean-Y
frequencyDomain-Body-Accelerometer-mean-Z
frequencyDomain-Body-Accelerometer-std-X
frequencyDomain-Body-Accelerometer-std-Y
frequencyDomain-Body-Accelerometer-std-Z
frequencyDomain-Body-Accelerometer-mean-Frequency-X
frequencyDomain-Body-Accelerometer-mean-Frequency-Y
frequencyDomain-Body-Accelerometer-mean-Frequency-Z
frequencyDomain-Body-Accelerometer-Jerk-mean-X
frequencyDomain-Body-Accelerometer-Jerk-mean-Y
frequencyDomain-Body-Accelerometer-Jerk-mean-Z
frequencyDomain-Body-Accelerometer-Jerk-std-X
frequencyDomain-Body-Accelerometer-Jerk-std-Y
frequencyDomain-Body-Accelerometer-Jerk-std-Z
frequencyDomain-Body-Accelerometer-Jerk-mean-Frequency-X
frequencyDomain-Body-Accelerometer-Jerk-mean-Frequency-Y
frequencyDomain-Body-Accelerometer-Jerk-mean-Frequency-Z
frequencyDomain-Body-Gyroscope-mean-X
frequencyDomain-Body-Gyroscope-mean-Y
frequencyDomain-Body-Gyroscope-mean-Z
frequencyDomain-Body-Gyroscope-std-X
frequencyDomain-Body-Gyroscope-std-Y
frequencyDomain-Body-Gyroscope-std-Z
frequencyDomain-Body-Gyroscope-mean-Frequency-X
frequencyDomain-Body-Gyroscope-mean-Frequency-Y
frequencyDomain-Body-Gyroscope-mean-Frequency-Z
frequencyDomain-Body-Accelerometer-Magnitude-mean
frequencyDomain-Body-Accelerometer-Magnitude-std
frequencyDomain-Body-Accelerometer-Magnitude-mean-Frequency
frequencyDomain-BodyBody-Accelerometer-Jerk-Magnitude-mean
frequencyDomain-BodyBody-Accelerometer-Jerk-Magnitude-std
frequencyDomain-BodyBody-Accelerometer-Jerk-Magnitude-mean-Frequency
frequencyDomain-BodyBody-Gyroscope-Magnitude-mean
frequencyDomain-BodyBody-Gyroscope-Magnitude-std
frequencyDomain-BodyBody-Gyroscope-Magnitude-mean-Frequency
frequencyDomain-BodyBody-Gyroscope-Jerk-Magnitude-mean
frequencyDomain-BodyBody-Gyroscope-Jerk-Magnitude-std
frequencyDomain-BodyBody-Gyroscope-Jerk-Magnitude-mean-Frequency
