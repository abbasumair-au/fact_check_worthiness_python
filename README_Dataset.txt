CHECKTHAT2018: Features and labels
--------------------------------------

This file describes the resources that are included in this folder.
There are four types of files such as train features, train labels, test features, and test labels.

Train features files
------------------------------------
train-NLECW-features-file1.csv
train-NLECW-features-file2.csv
train-NLECW-features-file3.csv
------------------------------------

Train labels files
------------------------------------
train-labels-file1.csv
train-labels-file2.csv
train-labels-file3.csv
------------------------------------

Test features files
------------------------------------
test-NLECW-features-task1-en-file1.csv
test-NLECW-features-task1-en-file2.csv
test-NLECW-features-task1-en-file3.csv
test-NLECW-features-task1-en-file4.csv
test-NLECW-features-task1-en-file5.csv
test-NLECW-features-task1-en-file6.csv
test-NLECW-features-task1-en-file7.csv
------------------------------------

Test features files
------------------------------------
test-labels-task1-en-file1.csv
test-labels-task1-en-file2.csv
test-labels-task1-en-file3.csv
test-labels-task1-en-file4.csv
test-labels-task1-en-file5.csv
test-labels-task1-en-file6.csv
test-labels-task1-en-file7.csv
------------------------------------

The first line of the (train/test) feature file is described as follows:
	SN: Sample number
	N(1--5): 5 Nutritional label based features
	L(1--136): 136 Linguistic features
	E(1--4): 4 Entity features
	C(1--338): 338 Category features
	W(1--300): 300 Word-embedding based features


The first line of the (train/test) label file is described as follows:
	SN: Sample number
	Label: 0 means negative class and 1 means positive
