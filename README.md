# Patika-Algoritma Ödev 

### Selection Sort
````
Answer:  
    Step 1: [2,3,5,8,7,9,4,15,6]
    Step 2: [2,3,4,8,7,9,5,15,6]
    Step 3: [2,3,4,5,7,9,8,15,6]
    Step 4: [2,3,4,5,6,9,8,15,7]
    
    Step 5: [2,3,4,5,6,7,8,15,9]
    Step 6: [2,3,4,5,6,7,8,9,15]
````
### Insertion Sort

````
Answer:
   Step 1: [22,27,16,2,18,6]   //block1 [22,27]
   Step 2: [22,16,27,2,18,6]   
   Step 3: [16,22,27,2,18,6]   //block2 [16,22,27]
   Step 4: [16,22,2,27,18,6]   
   Step 5: [16,2,22,27,18,6]   
   Step 6: [2,16,22,27,18,6]   //block3 [2,16,22,27]
   Step 7: [2,16,22,18,27,6]   
   Step 8: [2,16,18,22,27,6]   //block4 [2,16,18,22,27]
   Step 9: [2,16,18,22,6,27]   
   Step 10: [2,16,18,6,22,27]  
   Step 11: [2,16,6,18,22,27]  
   Step 12: [2,6,16,18,22,27]  //block5 [2,6,16,18,22,27]
````


Big O notation: O(n^2) hem selection sort hem insortion sort için geçerli.

18 sayısı ortada bulunduğu için average case durumuna girer.


### Merge Sort 
````
step 1: [16,21,11]              [8,12,22]

step 2: [16]    [11,21]         [8]      [12,22]

step 3: [16]    [11]    [21]    [8]     [12]    [22]

step 4: [11,16,21]       [8,12,22]

step 5: [8,11,12,16,21,22] end

````
Big O notation: O(logn)

### Binary search

```
[7,5,1,8,3,6,0,9,4,2]

root = 5 

                            5
                        1        7
                     0     3   6     8
                        2    4            9
```