****************************************************
****************************************************
                        lab07
****************************************************
****************************************************





****************************************************
Instruction:
1) Git Bash:
$ java -jar venus.jar . -dm
2) Venus:
mount local file
****************************************************




****************************************************
Exercise 1
Scenario 1

a0 = 128 bytes
sizeof(int) = 4 bytes
so there are 128/4 = 32 elements in array , array[0] , array[1] , array[2] , ... ,array[31]

a1(step size) = 8(elements)=32 (bytes) , need to check array[0] , array[8] , array[16] , array[24];

cache levels: only L1
Block Size : 8 bytes? or 8 elements?
Number of Blocks : 4
Placement Policy: Direct Mapped

Question:
1)How big is one cache block?
8 bytes.
2)How many consecutive accesses (taking into account the step size) fit within a single block?
0.
3)How much data fits in the WHOLE cache?
?
4)How far apart in memory are blocks that map to the same set (and could this create conflicts)?
?
5)What is your cache's associativity?
1.
6)Where in the cache does a particular block map to?
?
7)When considering why a specific access is a miss or hit: Have you accessed this piece of data before? If so, is it still in the cache or not?


skip Lab07, use http://staff.ustc.edu.cn/~llxx/cod/reference_srcs.html



