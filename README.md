# S7
V1
Target
•	Code setup
•	Defining the baseline Architecture 
•	Pointing the code to GPU
•	EDA to find mean & SD
Results
•	Total parameters is  2,435,744
•	Best Train Accuracy 63%
•	Best test Accuracy 62%
Analysis 
The gap b/w train and test is low but we need to improve the train accuracy and the total parameters should be less than 1 million.
V2
Target 
•	Image normalization
•	Image Augmentations
Results
•	Total parameters is  2,435,744
•	Best Train Accuracy 60%
•	Best test Accuracy 62%
Analysis 
Accuracy is not improving after trying various transformations
V3
Target
Refining the architecture to meet the total parameter target i.e. 1m
Results
•	Total parameters is  1,092,768
•	Best Train Accuracy 84 %
•	Best test Accuracy 81%
Analysis 
Improved accuracy, still parameter are > 1M

V4
Target
Implementing the depth wise convolution layer and adding dilated convolution and also refining the architecture to meet the total parameter target i.e. 1m
Results
•	Total parameters is  943,552
•	Best Train Accuracy 82 %
•	Best test Accuracy 81%
Analysis 
ACHEVIED 80% accuracy and total parameters are < 1M




