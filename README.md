## Ex.No.2A					Association Rules For Buying data set
## Date:22/5/25

## Aim:	
           To Find the Association Rules for Buying dataset.

## Description:

In data mining, association rule learning is a popular and well researched method for discovering interesting relations between variables in large databases. It can be described as analyzing and presenting strong rules discovered in databases using different measures of interestingness. In market basket analysis association rules are used and they are also employed in many application areas including Web usage mining, intrusion detection and bioinformatics.
Creation of Buying Table:

## Procedure:

1)Open Start  Programs  Accessories  Notepad
2)Type the following training data set with the help of Notepad for Buying Table.
```
@relation buying
@attribute age {L20,20-40,G40}
@attribute income {high,medium,low}
@attribute stud {yes,no}
@attribute creditrate {fair,excellent}
@attribute buyscomp {yes,no}
@data
L20,high,no,fair,yes
20-40,low,yes,fair,yes
G40,medium,yes,fair,yes
L20,low,no,fair,no
G40,high,no,excellent,yes
L20,low,yes,fair,yes
20-40,high,yes,excellent,no
G40,low,no,fair,yes
L20,high,yes,excellent,yes
G40,high,no,fair,yes
L20,low,yes,excellent,no
G40,high,yes,excellent,no
20-40,medium,yes,excellent,yes
L20,medium,yes,fair,yes
G40,high,yes,excellent,yes
```
3)After that the file is saved with .arff file format.
4)Minimize the arff file and then open Start  Programs  weka-3-4.
5)Click on weka-3-4, then Weka dialog box is displayed on the screen.
6)In that dialog box there are four modes, click on explorer.
7)Explorer shows many options. In that click on ‘open file’ and select the arff file
8)Click on edit button which shows buying table on weka.

## Procedure for Association Rules:

1)Open Start  Programs  Weka-3-4  Weka-3-4
2)Open explorer.
3)Click on open file and select buying.arff
4)Select Associate option on the top of the Menu bar.
5)Select Choose button and then click on Apriori Algorithm.
6)Click on Start button and output will be displayed on the right side of the window.

## Output:

Training Data Set  Buying Table
![2a1](https://github.com/kavyasenthamarai/WDM_EXP2/assets/118668727/f3fc9dd4-8e7e-418b-aa64-ea63f9cbfc25)

![2a2](https://github.com/kavyasenthamarai/WDM_EXP2/assets/118668727/cb2f3ba6-7448-4c7b-b16b-d90ca34d20cd)


## Result:

Thus this program has been successfully executed.








## Ex.No.2B					Association Rules For Banking Dataset

## Aim:	  
            To Find the Association Rules for Banking dataset.

## Description:

In data mining, association rule learning is a popular and well researched method for discovering interesting relations between variables in large databases. It can be described as analyzing and presenting strong rules discovered in databases using different measures of interestingness. In market basket analysis association rules are used and they are also employed in many application areas including Web usage mining, intrusion detection and bioinformatics.
Creation of Banking Table:

Procedure:

1)Open Start  Programs  Accessories  Notepad
2)Type the following training data set with the help of Notepad for Banking Table. 
```
@relation bank
@attribute cust {male,female}
@attribute accno{0101,0102,0103,0104,0105,0106,0107,0108,0109,0110,0111,0112,0113,0114,0115}
@attribute bankname {sbi,hdfc,sbh,ab,rbi}
@attribute location {hyd,jmd,antp,pdtr,kdp}
@attribute deposit {yes,no}
@data
male,0101,sbi,hyd,yes
female,0102,hdfc,jmd,no
male,0103,sbh,antp,yes
male,0104,ab,pdtr,yes
female,0105,sbi,jmd,no
male,0106,ab,hyd,yes
female,0107,rbi,jmd,yes
female,0108,hdfc,kdp,no
male,0109,sbh,kdp,yes
male,0110,ab,jmd,no
female,0111,rbi,kdp,yes
male,0112,sbi,jmd,yes
female,0113,rbi,antp,no
male,0114,hdfc,pdtr,yes
female,0115,sbh,pdtr,no
```
3)After that the file is saved with .arff file format.
4)Minimize the arff file and then open Start  Programs  weka-3-4.
5)Click on weka-3-4, then Weka dialog box is displayed on the screen.
6)In that dialog box there are four modes, click on explorer.
7)Explorer shows many options. In that click on ‘open file’ and select the arff file
8)Click on edit button which shows banking table on weka.

## Procedure for Association Rules:

1)Open Start  Programs  Weka-3-4  Weka-3-4
2)Open explorer.
3)Click on open file and select bank.arff
4)Select Associate option on the top of the Menu bar.
5)Select Choose button and then click on Apriori Algorithm.
6)Click on Start button and output will be displayed on the right side of the window.

## Output:
## Training Data Set  Banking Table
![2b1](https://github.com/kavyasenthamarai/WDM_EXP2/assets/118668727/81663f00-b8a3-49a1-8940-de404be37778)

![2b2](https://github.com/kavyasenthamarai/WDM_EXP2/assets/118668727/bfdb9760-ad26-44e8-abd5-3bc140c73536)

## Result:

Thus this program has been successfully executed.






## Ex.No.2C				Association Rules for Employee dataset

## Aim:  
            To Find the Association Rules for Employee data.

## Description:

In data mining, association rule learning is a popular and well researched method for discovering interesting relations between variables in large databases. It can be described as analyzing and presenting strong rules discovered in databases using different measures of interestingness. In market basket analysis association rules are used and they are also employed in many application areas including Web usage mining, intrusion detection and bioinformatics.
Creation of Banking Table:

## Procedure:

1)Open Start  Programs  Accessories  Notepad
2)Type the following training data set with the help of Notepad for Employee Table. 
```
@relation employee-1
@attribute age {youth, middle, senior}
@attribute income {high, medium, low}
@attribute class {A, B, C}

@data
youth, high, A
youth,medium,B
youth, low, C
middle, low, C
middle, medium, C
middle, high, A
senior, low, C
senior, medium, B
senior, high, B
middle, high, B
```
3)After that the file is saved with .arff file format.
4)Minimize the arff file and then open Start  Programs  weka-3-4.
5)Click on weka-3-4, then Weka dialog box is displayed on the screen.
6)In that dialog box there are four modes, click on explorer.
7)Explorer shows many options. In that click on ‘open file’ and select the arff file
8)Click on edit button which shows employee table on weka.

## Procedure for Association Rules:

1)Open Start  Programs  Weka-3-4  Weka-3-4
2)Open explorer.
3)Click on open file and select employee-1.arff
4)Select Associate option on the top of the Menu bar.
5)Select Choose button and then click on Apriori Algorithm.
6)Click on Start button and output will be displayed on the right side of the window.

## Output:
## Training Data Set  Employee Table
![2c1](https://github.com/kavyasenthamarai/WDM_EXP2/assets/118668727/1caf7ad9-ff97-417c-b60d-5acd2d23bdb3)
![2c2](https://github.com/kavyasenthamarai/WDM_EXP2/assets/118668727/9769a9cc-c161-4f98-a5ca-4c6b59ee8c29)


## Result:

Thus this program has been successfully executed.
