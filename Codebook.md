## Code Book

The following is the plain-English description of each variable found in my summary table for UC-Irvine’s Human Activity Recognition (HAR) dataset.  This dataset provides the raw data of an experiment testing the viability of smart phones as a wearable exercise tracking device.  The full dataset can be found here https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

UC – Irvine has made several of their test datasets available for public use.  

1:  **subject**: The Subject represents a human who tested the wearable devices.  Each person was randomly assigned to either a “test” or “train” group.  The “train” group were used as a control group on the smartphones, and the “test” group were compared to these baselines.

2:  **activity**: Each subject was measured performing six basic activities: Walking, Walking Upstairs, Walking Downstairs, Sitting, Standing, and Laying.

3:  **tBodyAcc-mean()-X**: This column represents the average mean of the device’s body accelerometer in the x direction

4:  **tBodyAcc-mean()-Y**: This column represents the average mean of the device’s body accelerometer in the y direction

5:  **tBodyAcc-mean()-Z**: This column represents the average mean of the device’s body accelerometer in the z direction

6:  **tGravityAcc-mean()-X**: This column represents the average mean of the device’s gravity accelerometer in the x direction

7:  **tGravityAcc-mean()-Y**: This column represents the average mean of the device’s gravity accelerometer in the y direction

8:  **tGravityAcc-mean()-Z**: This column represents the average mean of the device’s gravity accelerometer in the z direction

9:  **tBodyAccJerk-mean()-X**: This column represents the average mean of the device’s body accelerometer jerk in the x direction

10:  **tBodyAccJerk-mean()-Y**: This column represents the average mean of the device’s body accelerometer jerk in the y direction
11:  **tBodyAccJerk-mean()-Z**: This column represents the average mean of the device’s body accelerometer jerk in the z direction

12:  **tBodyGyro-mean()-X**: This column represents the average mean of the device’s body gyroscope in the x direction

13:  **tBodyGyro-mean()-Y**: This column represents the average mean of the device’s body gyroscope in the y direction

14:  **tBodyGyro-mean()-Z**: This column represents the average mean of the device’s body gyroscope in the z direction

15:  **tBodyGyroJerk-mean()-X**: This column represents the average mean of the device’s body gyroscope jerk in the x direction

16:  **tBodyGyroJerk-mean()-Y**: This column represents the average mean of the device’s body gyroscope jerk in the y direction

17:  **tBodyGyroJerk-mean()-Z**: This column represents the average mean of the device’s body gyroscope jerk in the z direction

18:  **tBodyAccMag-mean()**: This column represents the average mean of the total body linear acceleration magnitude

19:  **tGravityAccMag-mean()**: This column represents the average mean of the total gravity acceleration magnitude

20:  **tBodyAccJerkMag-mean()**: This column represents the average mean of the total body linear acceleration jerk magnitude

21:  **tBodyGyroMag-mean()**: This column represents the average mean of the total body gyroscope magnitude

22:  **tBodyGyroJerkMag-mean()**: This column represents the average mean of the total body gyroscope jerk magnitude

23:  **fBodyAcc-mean()-X**: This column represents the average mean of the Fourier Transform of the device’s body accelerometer in the x direction

24:  **fBodyAcc-mean()-Y**: This column represents the average mean of Fourier Transform of the device’s body accelerometer in the y direction

25:  **fBodyAcc-mean()-Z**: This column represents the average mean of Fourier Transform of the device’s body accelerometer in the z direction

26:  **fBodyAcc-meanFreq()-X**: This column represents the average frequency mean of the Fourier Transform of the device’s body accelerometer in the x direction

27:  **fBodyAcc-meanFreq()-Y**: This column represents the average frequency mean of the Fourier Transform of the device’s body accelerometer in the y direction

28:  **fBodyAcc-meanFreq()-Z**: This column represents the average frequency mean of the Fourier Transform of the device’s body accelerometer in the z direction

29:  **fBodyAccJerk-mean()-X**: This column represents the average mean of the Fourier Transform of the device’s body accelerometer jerk in the x direction

30:  **fBodyAccJerk-mean()-Y**: This column represents the average mean of the Fourier Transform of the device’s body accelerometer jerk in the y direction

31:  **fBodyAccJerk-mean()-Z**: This column represents the average mean of the Fourier Transform of the device’s body accelerometer jerk in the z direction

32:  **fBodyAccJerk-meanFreq()-X**: This column represents the average frequency mean of the Fourier Transform of the device’s body accelerometer jerk in the x direction

33:  **fBodyAccJerk-meanFreq()-Y**: This column represents the average frequency mean of the Fourier Transform of the device’s body accelerometer jerk in the y direction

34:  **fBodyAccJerk-meanFreq()-Z**: This column represents the average frequency mean of the Fourier Transform of the device’s body accelerometer jerk in the z direction

35:  **fBodyGyro-mean()-X**: This column represents the average mean of the Fourier Transform of the device’s body gyroscope in the x direction

36:  **fBodyGyro-mean()-Y**: This column represents the average mean of the Fourier Transform of the device’s body gyroscope in the y direction

37:  **fBodyGyro-mean()-Z**: This column represents the average mean of the Fourier Transform of the device’s body gyroscope in the z direction

38:  **fBodyGyro-meanFreq()-X**: This column represents the average frequency mean of the Fourier Transform of the device’s body gyroscope in the x direction

39:  **fBodyGyro-meanFreq()-Y**: This column represents the average frequency mean of the Fourier Transform of the device’s body gyroscope in the y direction

40:  **fBodyGyro-meanFreq()-Z**: This column represents the average frequency mean of the Fourier Transform of the device’s body gyroscope in the z direction

41:  **fBodyAccMag-mean()**: This column represents the average mean of the Fourier Transform of the device’s acceleration magnitude

42:  **fBodyAccMag-meanFreq()**: This column represents the average frequency mean of the Fourier Transform of the device’s acceleration magnitude

43:  **fBodyBodyAccJerkMag-mean()**: This column represents the average mean of the Fourier Transform of the body acceleration jerk magnitude

44:  **fBodyBodyAccJerkMag-meanFreq()**: This column represents the average frequency mean of the Fourier Transform of the body acceleration jerk magnitude 

45:  **fBodyBodyGyroMag-mean()**: This column represents the average mean of the Fourier Transform of the body gyroscope magnitude

46:  **fBodyBodyGyroMag-meanFreq()**: This column represents the average frequency mean of the Fourier Transform of the body gyroscope magnitude

47:  **fBodyBodyGyroJerkMag-mean()**: This column represents the average mean of the Fourier Transform of the body gyroscope jerk magnitude

48:  **fBodyBodyGyroJerkMag-meanFreq()**: This column represents the average frequency mean of the Fourier Transform of the body gyroscope jerk magnitude

49:  **tBodyAcc-std()-X**: This column represents the average standard deviation of the device body accelerometer in the x direction

50:  **tBodyAcc-std()-Y**: This column represents the average standard deviation of the device body accelerometer in the y direction

51:  **tBodyAcc-std()-Z**: This column represents the average standard deviation of the device body accelerometer in the z direction

52:  **tGravityAcc-std()-X**: This column represents the average standard deviation of the device gravity accelerometer in the x direction

53:  **tGravityAcc-std()-Y**: This column represents the average standard deviation of the device gravity accelerometer in the y direction

54:  **tGravityAcc-std()-Z**: This column represents the average standard deviation of the device gravity accelerometer in the z direction

55:  **tBodyAccJerk-std()-X**: This column represents the average standard deviation of the device accelerometer jerk in the x direction

56:  **tBodyAccJerk-std()-Y**: This column represents the average standard deviation of the device accelerometer jerk in the y direction

57:  **tBodyAccJerk-std()-Z**: This column represents the average standard deviation of the device accelerometer jerk in the z direction

58:  **tBodyGyro-std()-X**: This column represents the average standard deviation of the device body gyroscope in the x direction 

59:  **tBodyGyro-std()-Y**: This column represents the average standard deviation of the device body gyroscope in the y direction

60:  **tBodyGyro-std()-Z**: This column represents the average standard deviation of the device body gyroscope in the z direction

61:  **tBodyGyroJerk-std()-X**: This column represents the average standard deviation of the device body gyroscope jerk in the x direction 

62:  **tBodyGyroJerk-std()-Y**: This column represents the average standard deviation of the device body gyroscope jerk in the y direction

63:  **tBodyGyroJerk-std()-Z**: This column represents the average standard deviation of the device body gyroscope jerk in the z direction

64:  **tBodyAccMag-std()**: This column represents the average standard deviation of the device body accelerometer magnitude 

65:  **tGravityAccMag-std()**: This column represents the average standard deviation of the device gravity accelerometer magnitude

66:  **tBodyAccJerkMag-std()**: This column represents the average standard deviation of the device body accelerometer jerk magnitude

67:  **tBodyGyroMag-std()**: This column represents the average standard deviation of the device body gyroscope magnitude

68:  **tBodyGyroJerkMag-std()**: This column represents the average standard deviation of the device body gyroscope jerk magnitude

69:  **fBodyAcc-std()-X**: This column represents the average standard deviation of the Fourier Transform of the device body accelerometer in the x direction

70:  **fBodyAcc-std()-Y**: This column represents the average standard deviation of the Fourier Transform of the device body accelerometer in the y direction

71:  **fBodyAcc-std()-Z**: This column represents the average standard deviation of the Fourier Transform of the device body accelerometer in the z direction

72:  **fBodyAccJerk-std()-X**: This column represents the average standard deviation of the Fourier Transform of the device body accelerometer jerk in the x direction

73:  **fBodyAccJerk-std()-Y**: This column represents the average standard deviation of the Fourier Transform of the device body accelerometer jerk in the y direction

74:  **fBodyAccJerk-std()-Z**: This column represents the average standard deviation of the Fourier Transform of the device body accelerometer jerk in the z direction

75:  **fBodyGyro-std()-X**: This column represents the average standard deviation of the Fourier Transform of the device body gyroscope in the x direction

76:  **fBodyGyro-std()-Y**: This column represents the average standard deviation of the Fourier Transform of the device body gyroscope in the y direction

77:  **fBodyGyro-std()-Z**: This column represents the average standard deviation of the Fourier Transform of the device body gyroscope in the z direction

78:  **fBodyAccMag-std()**: This column represents the average standard deviation of the Fourier Transform of the device body accelerometer magnitude 

79:  **fBodyBodyAccJerkMag-std()**: This column represents the average standard deviation of the Fourier Transform of the device body accelerometer magnitude

80:  **fBodyBodyGyroMag-std()**: This column represents the average standard deviation of the Fourier Transform of the device body gyroscope magnitude

81:  **fBodyBodyGyroJerkMag-std()**: This column represents the average standard deviation of the Fourier Transform of the device body gyroscope jerk magnitude


