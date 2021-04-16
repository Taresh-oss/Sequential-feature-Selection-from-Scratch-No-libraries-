Here I implement the sequential forward selection algorithm to identify important features. The program will take one input: a dataset where the last column is the class variable. 
The program will load the dataset, and then use wrapper approach with sequential forward selection strategy to find a set of important features.  
- stratified cross validation 5-fold is used for measuring accuracy  
- Features keep on adding as long as classification accuracy keeps on improving. 
- The output of the program is set of important features on the console. 
- A function has been written to calculate accuracy using stratified 5 fold cross validation. 
