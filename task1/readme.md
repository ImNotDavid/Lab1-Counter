# Task 1
After following the instructions to complete task 1 up to creating the doit.sh script to automatically complete the entire process.
<br>
For the first extension task, to pause the counter for 3 cycles once it reaches 9, I modified the en and rst conditions in the testbench from:
~~~c++
top->rst = (i<2) | (i==15);
top->en = (i>4);
~~~