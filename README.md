# LeetCode-204

Step 1: create a vector to contain the number(from 1 to n-1) is a prime, initialize the value to be true; creat int prime to count the number of primes;
Step 2: set the limitation(limit = sqrt(n))for increasing int i, in order to make the test will not out of bound;
Step 3: Using nested for loop to select the prime:
       step 3.1: using the concept that all the prime's multiples cannot be the prime, and remove them form the array starts from the first prime to n-1;
       step 3.2: overwrite the value of non-prime to the false; then all the true value element should be the prime;
Step 4: Using another for loop to pass all the element of vector, if the element is true, then do accumulating of the int prime; 
