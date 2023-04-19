# Intruder_Detection_YOLOV7
Build a model that detects Intruders(humans)


## Objective of this notebook
- The purpose of this notebook is to build model capable of detecting intruders
- The algorithm of choice here is YOLOV7 and we would be custom training YOLOV7 on an aerial imagery datatset
- Details of the **Problem Statement**  , **Data Set** , **Data Pre-processing & Splits**,  **Architecture/Algorithm** , **Summary of the Code/Solution**  , **Sample Output/Prediction** from the program and **Final Result** of the project are listed in the sections to follow.

## Problem Statement 
Computer vision can be used to pro-actively detect intruders


## Data Description:
NA
 
## Domain:
   Surveillance

## Data Pre-processing & Splits:
NA
 
 
 ## Architecture/Algorithm:
 YOLOV7 by https://github.com/WongKinYiu/yolov7

## Summary of the Solution/Code:
The code aims at running YOLOV7 out of the box on intruder images and capture results
- The YOLOV7 API used in this notebook is @https://github.com/WongKinYiu/yolov7 by WonkinYui
- In this notebook we firsy explore/Sanity test on  YOLOV7  API as is and run some general inferences
- The task at hand is to use YOLOV7 to detect intruders. YOLOV7 has been pre-trained on a dataset where 'human' or 'person' is already present as a class.Therefore , we can use YOLOV7 out of the box for intruder detection, we do not need to custom train it on 'human' data
- We then Publish scores
- Run a couple of inferences on  images

## Sample Ouput/Prediction :
Here are a couple of Sample Ouput images from  the program/model .

![image](https://user-images.githubusercontent.com/68383273/233135191-268c9784-96c8-44ce-9249-39ca4e8127a8.png)
![image](https://user-images.githubusercontent.com/68383273/233135353-55d9009c-51aa-400a-9260-befb48808d11.png)




## Result

![image](https://user-images.githubusercontent.com/68383273/233134944-3300dab6-2826-4716-a68a-591e0286add2.png)



## References & Guidance
NA


