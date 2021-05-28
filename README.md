# Canopy-Clustering
Implementation of Canopy clustering algorithm using c++.


Readme for running the code.

Steps

1. Open terminal in present directory.

2. Compile the code using command  "g++  canopyClustering.cpp -o canopy".

3. Run the code using "./canopy input1.txt". Here one argument is passed which is input file name which is present in current directory.

4. Get output on terminal.


Note. input1.txt is a normal 2 dimentional input while input2.txt is the original "iris dataset".

Input form: -

 cin >>total_points>> total_dimensions >>t1>>t2>>has_name;

 That means in the first line of input we have total points in data, total dimensions(like in case 2D enter 2,in case 3D enter 3), t1,t2, has_name( If data set has naming like in iris data set enter 1 otherwise 0)

 Now in number of lines equals total points,in each line first enter dimension wise input then name(if has name is 1 otherwise leave it).
  
 Ex  - 
 
case 1:
 2 3 5 4 1
 2 5 6 ram
 4 9 7 mohan

case 2:
 2 3 5 4 0
 2 5 6 
 4 9 7 

Output-

Each clusters of points are printed on terminal.
Note- If you run program again with same input output may or may not be same because we are randomly selecting point for canopy(as per algorithm)
