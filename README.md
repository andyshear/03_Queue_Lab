03_Queue_Lab
============

Implement an array-based queue in C++

Requirements
------------

1. remove takes O(1) time
2. add takes O(1) time, unless it calls grow (in that case O(n) is okay)
3. grow is only called if the number of items == backingArraySize, and the size of the array is doubled during grow
4. grow takes O(n) time
5. Do not leak memory (make sure grow and the destructor do the right thing)
6. getNumItems is O(1) time
7. add and remove throw excpetions as appropriate
8. You must use the array in a circular fashion. If you don't do this you probably won't be able to get #1, #2 and #3 to all be true.

Questions
=========

#### 1. Which of the above requirements work, and which do not? For each requirement, write a brief response.

1. TODO
2. TODO
3. TODO
4. TODO
5. TODO
6. TODO
7. TODO
8. TODO

#### 2. If we did a Stack instead of a Queue, which of the private methods and variables would we need to keep, and which could we get rid of? Explain your answer.

#### 3. What is one question that confused you about this excercise, or one piece of advice you would share with students next semester?

#### 4. In Java you might write "class ArrayQueue extends Queue" ... how do you write the same thing in C++?

#### 5. What is the purpose of "templates" in C++?

#### 6. What would the syntax be for dynamically allocating an array of 10 ints, in C++?

#### 7. What is the purpose of a class destructor in C++? Why don't you need them in Java?