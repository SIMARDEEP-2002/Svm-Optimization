# Parameter Optimization of SVM


## Dataset

The dataset for the project has been taken from the UCI.
[https://archive.ics.uci.edu/ml/machine-learning-databases/letter-recognition/](https://archive.ics.uci.edu/ml/machine-learning-databases/letter-recognition/)

Data Set Characteristics:  

Multivariate

Number of Instances:20000

Number of Attributes:16

Attribute Information:

1. lettr capital letter (26 values from A to Z)
2. x-box horizontal position of box (integer)
3. y-box vertical position of box (integer)
4. width width of box (integer)
5. high height of box (integer)
6. onpix total # on pixels (integer)
7. x-bar mean x of on pixels in box (integer)
8. y-bar mean y of on pixels in box (integer)
9. x2bar mean x variance (integer)
10. y2bar mean y variance (integer)
11. xybar mean x y correlation (integer)
12. x2ybr mean of x * x * y (integer)
13. xy2br mean of x * y * y (integer)
14. x-ege mean edge count left to right (integer)
15. xegvy correlation of x-ege with y (integer)
16. y-ege mean edge count bottom to top (integer)
17. yegvx correlation of y-ege with x (integer)


The objective is to identify each of a large number of black-and-white rectangular pixel displays as one of the 26 capital letters in the English alphabet. The character images were based on 20 different fonts and each letter within these 20 fonts was randomly distorted to produce a file of 20,000 unique stimuli. Each stimulus was converted into 16 primitive numerical attributes (statistical moments and edge counts) which were then scaled to fit into a range of integer values from 0 through 15. We typically train on the first 16000 items and then use the resulting model to predict the letter category for the remaining 4000.





## Result Table

| Sample  | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
| -----   | ------------- | ----------- | ------- | ------------ |
| 1 | 0.93| poly | 0.40 | 0.79 |
| 2 | 0.93| poly | 0.76 | 0.59 |
| 3 | 0.96 | rbf | 0.64 | 0.10 |
| 4 | 0.91 | poly | 0.38 | 0.29 |
| 5 | 0.94 | poly | 0.42 | 0.01 |
| 6 | 0.92 | rbf | 0.18 | 0.39 |
| 7 | 0.94 | poly| 0.58| 0.15 |
| 8 | 0.92 | poly | 0.70 | 0.95 |
| 9 | 0.92 | poly| 0.95 | 0.21 |
| 10 | 0.92 | poly | 0.80 | 0.71 |

## Graph
<img width="615" alt="result" src="https://user-images.githubusercontent.com/79918370/233186155-bbb34947-e493-47e4-ab41-cf4eeb8b5106.png">



## Project Submitted By

Sub-Group: COE 22

Name : Simardeep Singh 

Roll No. : 102003559



