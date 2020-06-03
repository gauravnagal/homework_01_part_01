# Clustering Example

# Homework_01
## Data Generation Script for Homework 01

#### Part 01:
- Use Data Generation script to create sample data for 
using clustering algorithms to determine clusters for both
examples. Algorithms to use:  
    - KMeans
    - DBScan
    - Choice of others that works best.
    
- Train a TensorFlow classifier to take a point in a 
two dimensional plane and classify it as one of the clusters
from KMeans.

- The part of the assignment should be submitted as a
Jupyter Notebook.

#### Part 02:
- Create a Flask service which has the following endpoints:
    - `/heartbeat`
        - Returns the typical heartbeat return.
    - `/sum`
        - Accept values in the form _x_ and _y_ and return _x+y_
        
    - `/minimum`
        - Accept a list with the key `values` in the form
        and return the minimum value in the list.
        
    - `/product`
        - Accept a list of numbers with the key `value`
        and return the product of all the numbers.  If no values
        in the list, return 0.
        
