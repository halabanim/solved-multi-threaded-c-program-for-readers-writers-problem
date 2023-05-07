Download Link: https://assignmentchef.com/product/solved-multi-threaded-c-program-for-readers-writers-problem
<br>
5/5 - (3 votes)

Write a multi-threaded C program for readers/writers problem using Pthreads. This program should adhere to the following constraints:



1. Multiple readers/writers must be supported (at least 4 of each type);

2. Readers must read the shared variable multiple times (at least 4 times);

3. Writers must write the shared variable multiple times (at least 4 times);

4. Readers must print:

a. The reader thread ID,

b. The value of the shared variable,

c. The number of readers present when value is read;

5. Writers must print:

a. The writer thread ID,

b. The written value to the shared variable,

c. The number of readers present were when value is written.

The print out can be implemented using fprintf(). A sample code can be found in readerswriters.c. Before a reader/writer attempts to access the shared variable, it should wait some random amount of time. This will help ensure that reads and writes do not occur all at once. For this purpose, you can use srandom() and usleep().