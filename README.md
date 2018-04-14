## Calculation of Average Precision (natural) and Mean Average Precision (natural)
* For the purpose of this assignment, two files were provided, ```qrels.test``` and ```results.test```.
* This program will read the files and cenvert them into a ```pandas``` data frame
* A *merge*, i.e., inner join will be performed on the two data frames
* An evaluation table will be calculated containing the following coloumns: **qid**, **did**, **rel**, **rank**
* Using the above evaluation table, the average precision for each query topic is calculated
* Finally the MAP for the entire query topic set is calculated
