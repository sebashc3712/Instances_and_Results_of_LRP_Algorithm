# Instances_and_Results_of_LRP_Algorithm

Instances (modification of classic 3L-CVRP instances) and results of the LRP Algorithm.

## Structure of the repository

  + Files to run: files of the modified 3L-CVRP instances with relocations points
  
  + ILOG Intances: files of the models for ILOG and their results of each instance
  
  + Instances 3L-CVRP: files with the description of the original classic instances
  
  + Results: results of the LRP Algorithm (with and without traditional packing) on the "files to run"
  
## How to read the files to run?

The reading of files is the same of the classics but the last part (a long list with three numbers per row). These are the relocation points per customer. They are three for each customer. So the first three belongs to the first customer, the next three to the second customer and so on.

## Note

In the results folder the Instance numbers correspond to the testInput file from 1 to 9. That, means the file with "I1" corresponds to testInput, the file with "I2" corresponds to testInput2 and so on until "I9". Then, the "I10" corresponds to the testInput11, the "I11" corresponds to the testInput12 and so until "I26". The Solution with "I27" corresponds to the testInput10. 
