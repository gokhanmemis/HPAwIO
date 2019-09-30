# HPAwIO Dataset

HPAwIO is a Physical Activity dataset. This dataset contains mobile phone and oximeter sensors data and labeled with Physical Activity with Indoor and Outdoor information. 

Please **DO NOT** modify this dataset directly.


## **Dataset Information**


The recorded dataset contains data from 4 different physical activities and for 2 different locations. All physical activities in the protocol were carried out for about 10 minutes. It was collected more than 16 hours of data using the sensors, labeled as one of 4 different PAs for 2 different locations during data collection. All twelve male and female subjects performed all the activities. In addition, data collection was performed at different times during the day. These hours were from 7 am to 11 am in the morning, from 12 pm to 4 pm in the afternoon, and from 6 pm to 12 am in the evening. This dataset contains 27 features and one class value. Each record consisted of the accelerometer, Gyroscope, Magnetometer, Clinometer, and oximeter signals and was annotated by physical activitie label. All collected records were divided into 3 different age groups, namely Group-A (age between 18 - 34), Group-B (age between 35 - 54), and Group-C (age between 55 - 65). Each subject performed all PAs and we labeled the records with a granularity of 1 millisecond. There are 8 different files consisting of such data, for each subject.


## **Dataset Sumary**

- Labels : Indoor Walking, Outdoor Walking, Indoor Running, Outdoor Running, Indoor Sitting, Outdoor Sitting, Indoor Standing, Outdoor Standing
- Feature Count : 27 
- Number Of Subjects : 12
- Number Of Activities : 8
- Sensor Placement : Right trouser pocket, right hand, left forefinger
- Sampling Rate : 200Hz
- Number of Samples : 13959902

## **Citation Request**

Use of this dataset in publications must be acknowledged by referencing the following publication:

>Memis G. and Sert M., "Detection of Basic Human Physical Activities With Indoor–Outdoor Information Using Sigma-Based Features and Deep Learning," in IEEE Sensors Journal, vol. 19, no. 17, pp. 7565-7574, 1 Sept.1, 2019. doi: 10.1109/JSEN.2019.2916393

We recommend to refer to this dataset as the 'HPAwIO Dataset' in publications.  
We would appreciate if you send us an email (gokhanmemis@gmail.com) to inform us of any publication using this dataset.

## **Label Set**
- INDOOR_WALKING : 0
- OUTDOOR_WALKING: 1
- INDOOR_STANDING: 2
- OUTDOOR_STANDING: 3
- INDOOR_SITTING: 4
- OUTDOOR_SITTING: 5
- INDOOR_RUNNING: 6
- OUTDOOR_RUNNING: 7

## **Attribute Information**

>@attribute Column_1:_acceleration_from_the_hand_sensor_(X_axis) numeric
@attribute Column_2:_acceleration_from_the_hand_sensor_(Y_axis) numeric
@attribute Column_3:_acceleration_from_the_hand_sensor_(Z_axis) numeric
@attribute Column_4:_gyro_from_the_hand_sensor_(X_axis) numeric
@attribute Column_5:_gyro_from_the_hand_sensor_(Y_axis) numeric
@attribute Column_6:_gyro_from_the_hand_sensor_(Z_axis) numeric
@attribute Column_7:termometer numeric
@attribute Column_8:_magnetometer_from_the_hand_sensor_(X_axis) numeric
@attribute Column_9:_magnetometer_from_the_hand_sensor_(y_axis) numeric
@attribute Column_10:_magnetometer_from_the_hand_sensor_(z_axis) numeric
@attribute Column_11:_clinometer_from_the_hand_sensor_(X_axis) numeric
@attribute Column_12:_clinometer_from_the_hand_sensor_(y_axis) numeric
@attribute Column_13:_clinometer_from_the_hand_sensor_(z_axis) numeric
@attribute Column_14:_acceleration_from_the_trousers_sensor_(X_axis) numeric
@attribute Column_15:_acceleration_from_the_trousers_sensor_(Y_axis) numeric
@attribute Column_16:_acceleration_from_the_trousers_sensor_(Z_axis) numeric
@attribute Column_17:_gyro_from_the_trousers_sensor_(X_axis) numeric
@attribute Column_18:_gyro_from_the_trousers_sensor_(Y_axis) numeric
@attribute Column_19:_gyro_from_the_trousers_sensor_(Z_axis) numeric
@attribute Column_20:termometer numeric
@attribute Column_21:_magnetometer_from_the_trousers_sensor_(X_axis) numeric
@attribute Column_22:_magnetometer_from_the_trousers_sensor_(y_axis) numeric
@attribute Column_23:_magnetometer_from_the_trousers_sensor_(z_axis) numeric
@attribute Column_24:_clinometer_from_the_trousers_sensor_(X_axis) numeric
@attribute Column_25:_clinometer_from_the_trousers_sensor_(y_axis) numeric
@attribute Column_26:_clinometer_from_the_trousers_sensor_(z_axis) numeric
@attribute Column_27:oxigen_saturation numeric
@attribute Column_28:pulse numeric
@attribute class {0,1,2,3,4,5,6,7}





