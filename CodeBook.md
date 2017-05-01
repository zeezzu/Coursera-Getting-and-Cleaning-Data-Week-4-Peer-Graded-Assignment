# Codebook

There are 68 columns in this data set. Each row contains data related to 1 activity for a certain person.

There are data for 30 persons, each one was tracked for 6 activities, so there are a total of 180 rows of data.

Each row contains data for 66 variables, each one being the average of the raw data for the corresponding person/activity combination.

## Basic data

* SubjectId - Number between 1 and 30 representing the person who has the data
* ActivityName - It can be one of these values: WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING

## Variables

There are a lot of variables each one measuring one kind of data. They are all listed bellow.

You can identify their meaning by examining how each variable is named:

1) Variables starting with "FrequencyDomain" contains data after the Fast Fourier Transform.
2) Variables starting with "TimeDomain" contains raw data, before the Fast Fourier Transform.
3) Variables ending with "Mean" or "MeanX/Y/Z" contains the mean value of the data or for its axis.
4) Variables ending with "Std" or "StdX/Y/Z" contains the standard deviation of the data or for its axis.
5) The middle of the variable name contains what exactly is the data and its procedence, if it was taken from the accelerometer or from the gyroscope.

* FrequencyDomainBodyAccelerometerJerkMeanX
* FrequencyDomainBodyAccelerometerJerkMeanY
* FrequencyDomainBodyAccelerometerJerkMeanZ
* FrequencyDomainBodyAccelerometerJerkStdX
* FrequencyDomainBodyAccelerometerJerkStdY
* FrequencyDomainBodyAccelerometerJerkStdZ
* FrequencyDomainBodyAccelerometerMagnitudeMean
* FrequencyDomainBodyAccelerometerMagnitudeStd
* FrequencyDomainBodyAccelerometerMeanX
* FrequencyDomainBodyAccelerometerMeanY
* FrequencyDomainBodyAccelerometerMeanZ
* FrequencyDomainBodyAccelerometerStdX
* FrequencyDomainBodyAccelerometerStdY
* FrequencyDomainBodyAccelerometerStdZ
* FrequencyDomainBodyBodyAccelerometerJerkMagnitudeMean
* FrequencyDomainBodyBodyAccelerometerJerkMagnitudeStd
* FrequencyDomainBodyBodyGyroscopeJerkMagnitudeMean
* FrequencyDomainBodyBodyGyroscopeJerkMagnitudeStd
* FrequencyDomainBodyBodyGyroscopeMagnitudeMean
* FrequencyDomainBodyBodyGyroscopeMagnitudeStd
* FrequencyDomainBodyGyroscopeMeanX
* FrequencyDomainBodyGyroscopeMeanY
* FrequencyDomainBodyGyroscopeMeanZ
* FrequencyDomainBodyGyroscopeStdX
* FrequencyDomainBodyGyroscopeStdY
* FrequencyDomainBodyGyroscopeStdZ
* TimeDomainBodyAccelerometerJerkMagnitudeMean
* TimeDomainBodyAccelerometerJerkMagnitudeStd
* TimeDomainBodyAccelerometerJerkMeanX
* TimeDomainBodyAccelerometerJerkMeanY
* TimeDomainBodyAccelerometerJerkMeanZ
* TimeDomainBodyAccelerometerJerkStdX
* TimeDomainBodyAccelerometerJerkStdY
* TimeDomainBodyAccelerometerJerkStdZ
* TimeDomainBodyAccelerometerMagnitudeMean
* TimeDomainBodyAccelerometerMagnitudeStd
* TimeDomainBodyAccelerometerMeanX
* TimeDomainBodyAccelerometerMeanY
* TimeDomainBodyAccelerometerMeanZ
* TimeDomainBodyAccelerometerStdX
* TimeDomainBodyAccelerometerStdY
* TimeDomainBodyAccelerometerStdZ
* TimeDomainBodyGyroscopeJerkMagnitudeMean
* TimeDomainBodyGyroscopeJerkMagnitudeStd
* TimeDomainBodyGyroscopeJerkMeanX
* TimeDomainBodyGyroscopeJerkMeanY
* TimeDomainBodyGyroscopeJerkMeanZ
* TimeDomainBodyGyroscopeJerkStdX
* TimeDomainBodyGyroscopeJerkStdY
* TimeDomainBodyGyroscopeJerkStdZ
* TimeDomainBodyGyroscopeMagnitudeMean
* TimeDomainBodyGyroscopeMagnitudeStd
* TimeDomainBodyGyroscopeMeanX
* TimeDomainBodyGyroscopeMeanY
* TimeDomainBodyGyroscopeMeanZ
* TimeDomainBodyGyroscopeStdX
* TimeDomainBodyGyroscopeStdY
* TimeDomainBodyGyroscopeStdZ
* TimeDomainGravityAccelerometerMagnitudeMean
* TimeDomainGravityAccelerometerMagnitudeStd
* TimeDomainGravityAccelerometerMeanX
* TimeDomainGravityAccelerometerMeanY
* TimeDomainGravityAccelerometerMeanZ
* TimeDomainGravityAccelerometerStdX
* TimeDomainGravityAccelerometerStdY
* TimeDomainGravityAccelerometerStdZ
