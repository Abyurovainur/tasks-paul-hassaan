# Problem F #
## Ordering Tasks ##
Input: standard input<br />
Output: standard output<br />
Time Limit: 1 second<br />
Memory Limit: 32 MB<br />
<br />
John has n tasks to do. Unfortunately, the tasks are not independent and the execution of one task is only possible if other tasks have already been executed.
## Input ##
<br />
The input will consist of several instances of the problem. Each instance begins with a line containing two integers, 1 <= n <= 100 and m. n is the number of tasks (numbered from 1 to n) and m is the number of direct precedence relations between tasks. After this, there will be m lines with two integers i and j, representing the fact that task i must be executed before task j. An instance with n = m = 0 will finish the input.<br />
<br />
## Output ##
<br />
For each instance, print a line with n integers representing the tasks in a possible order of execution.<br />
<br />
## Sample Input ##
<br />
5 4<br />
1 2<br />
2 3<br />
1 3<br />
1 5<br />
0 0<br />
<br />
## Sample Output ##
<br />
1 4 2 5 3<br />