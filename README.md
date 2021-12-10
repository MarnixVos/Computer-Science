# Computer-Science

This project implements a duplicate detection algorithm to find duplicate products in a TV data set.

The code executes the following methods:

Bootstrap 10 times using 1000 of 1642 products, for each bootstrap: 
  1. Get the model words
  2. One hot encode model words
  3. Create minhash signature of sparse binary vectors
  4. Implement LSH to generate canidate pairs
  5. Use custom classification to determine duplicate pairs
  6. Grab performance measures (PC, PQ, F1 and F1* measure) 
Report the average performance across 10 bootstraps. 

The way to run the code is quite simple: 
  1. Mount your drive
  2. Upload your json file and open in the #Grab JSON file block
  3. The helper function and main function code block load all the function, hyperparams can be set in the hyperparam block 
  4. Run the boostrapping block to get the performance estimates
  5. Run the last block to output the average performance 


This program is coded in Python, up to step 3 everything is coded using numpy arrays to improve efficiency. 
