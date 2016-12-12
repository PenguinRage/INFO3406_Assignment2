# INFO3406_Assignment2
Machine Learning on CriteoLab's Kaggle Display Advertising Challenge dataset
## Description
This is a quick readme file discussing the specifications for the assignment submitted.
Please take the time to read the submitted instructions on how to run the code.
## Requirements
- Python3
- all Anaconda libraries

## Running the code

#### Files needed
The cifar10 and cifar100 files need to be downloaded unziped and placed in the INFO3406_Assignment1 folder in order to run this program

#### Assignment2.ipynb
This can be run by uploading it into a jupyter notebook running on the virtual machine provided to us within the assignment specification.

dac_sample.tar.gz also needs to be uploaded to the same directory as the notebook in order for the data to be extracted correctly and utilized further in the code.

When running the code inside a jupyter notebook please allow each cell to execute before starting the next attempting to run one before another has finished may cause errors.

In order to run this code with multiple cores please adjust the core count of the virtual machine through virtualbox before initialising it.

#### Possible Adjustments:
On the third line there is of our solution there is a line reading clean_items = items.fetch(14) this caused execution problems on one of our test machines if such any such problem occurs pleas comment out this line and attempt to run the code again.

The k value of our k-nn can be changed in the second cell of our notebook if needed.
