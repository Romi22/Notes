# Notes
Notes on DSA in Java


What is Data Structure?

 Data Structures are ways of organizing data on our computer, that can be used effectively.

 All applications are dealing with data so they do some operations based on the given data. Before processing the data we have to organise the data
 in a certain way that makes the process very efficient.

 From software applications performance point of view, the efficiency and the performance of the software depend on how the data is stored, organised,
 and grouped together during program execution.

 Everyday during our daily lives we can see different types of data structures.

 1. There might be a crowd of people who want to get a ticket for the concert. But without organised way, it becomes almost impossible to get a ticket.
   the organised way of people to get ticket is QUEUE which is First In First Out method.

2. Imagine there are bunch of books on the table and I want to return them to the library. It's obvious that without an organized way  of ordering, we cannot
    carry these books.
       On other hand if I order them in a way, it becomes easier to carry. And this reminds us of of STACK, First In Last Out Data Structure.

A professional software developer has to know which data structure to choose for a particular app, which has the direct effect on the performance.



What is an Algorithm?

Set of instructions to perform a task.

1. Suppose we want to choose wooden items for flooring, we need to accomplish several tasks.

Step1 - Choose flooring.

Step2 - Purchase and bring

Step3 - Prepare sub flooring

Step4 - Determine the layout

Step5 - Trim door casing


First we structure woods as data structure. Then we completed the steps which is a set of rules, as mentioned in the definition of algorithm.
So to make flooring we need follow these 5 steps over here. So these steps together is called an algorithm which is a set of instructions to complete tasks.


Algoritms in our daily lives :

Algorithm fromgetting home to Work.

1. Go to bus stop
2. Take a bus.
3. Go to office


Algorithm of buying a coffee from starbucks

1. Go to starbucks
2. Order a coffee
3. Pay the Amount
4. Take a coffee


Algorithm in Computer Science : Set of rules for a computer program to accomplish a task.
Learning about different types of algorithms and knowing when to apply them allows us to write time and memory efficient programs.

Sample algorithms that are used by Big companies.

1. How do Google and Facebook transmit live videos across the Internet?

So the answer is they are using Audio and video Compression algorithm to transmit videoly lively.

2. How to find shortest path on the map?

Graph Algorithms are used in Google, Apple or microsoft to find the shortest path between two locations.

3. How to arrange solar panels on International Space station?

Optimization and schedulling algorithms are used by NASA to arrange solar panels on International Space station

Good Algorithms:

1. Correctness (solves the problem correctly)

2. Efficiency (it does it so efficiently)


Why Data Structures and Algorithms are important ?

First we take data as an input, then we process it, and then we give back processed data as an output

1. When we search for a direction on Google Map we provide the starting and the endpoint as an input to the Google Map.
   it processed this data by using some processing operations and then find the shortest path between this location and it provides as output to us over here.
   To make this process efficient we need to optimize all the three steps over here.

      it is very obvious that the most we can optimize is the second step where we have data structures and algorithms.

      So by using graph data structures or Dijkstra's shortest path algorithm Google map is able to find the shortest path between the provided points very efficiently.


 By now we know Data Structures refer the way we organise our computer. So this has a great impact on the performance.

 2. Suppose that we want to have books on algorithms from library. To get it first we go the computer science section , then to algorithms section.
   As we can see it is easy to find book that we need.
      On the other hand if these books are not organised in this manner just randomly distributed. It is always impossible to find the book that we need.This is a way a
      librarian organises in a particular form to efficiently perform the task on it.

      here books are the data and arranging them is a data structure and finding a book that we need is an algorithm.

  Computer Science process and looks for the best way to organise the data so that it can be processed based on input provided.

Why Data Structures and Algorithms in Interview?

1. Problem Solving skills.

2. Todays computer comes with more meomory, if developer doesn't handle memory management technique the program may leak and lose the memory. This means
without understanding data structures code may end up with a memory leak.


Types of Data Structures:
these groups are either predefined in the programming language or defined by the user.

1. PRIMITIVE

      Integer
      Float
      Character
      Boolean


2. NON PRIMITIVE



 Linear

     items are arranged in memory in linear sequential manner and they can be either static or Dynamic.

     In static linear structure sizes and structures associated with memory locations are fixed at a compile time
      e.g. Array

     In dynamic structures associated memory location change.
     e.g. Linked List
     STACK
     QUEUE


 Non-Linear

 Data is connected to several other items and not organised sequentially. Here it's possible for a data item can be connected with more than one data items

 e.g. tree
 graph



 NOTE : Each of these data structures over here has its own unique properties which work very efficiently in different circumstances.
 Graph DS works perfectly for Maps
 Stack DS works perfectly when you have backward and forward buttons in our application due to its FILO nature.


 TYPES OF ALGORITHMS :

 Algorithms can be classified based on the problem they are trying to solve, such as sorting algorithms, searching and so on..
 or they can be classified based on problem solving approach


 1. Simple recursive algorithms
 2. Divide and conquer algorithms
 3. Dynamic Programming algorithms
 4. Greedy algorithms
 5. Brute Force algorithms
 6. Randomized

 1. Simple recursive algorithms

 Such algo works in a way as iterative algorithms

 The recursion acts as a loop

 we can think of an algo that calls itself


  2. Divide and conquer algorithms

  This type of algo consists of two parts :

  a. Divide the problem into smaller subproblems of the same type, and solve these problems recursively.
  b. Combine the solutions to the subproblems into a solution to the original problem.

  Example - Quick & Merge sort

  Traditionally an algo is called Divide and conquer if it contains at least two recursive calls.

  3. Dynamic Programming Algorithm

  a. They worked based on memorization.

  b. to find the best solution.

  These types of algo are generally used for optimization problems.
  The goal is to find the best soln among multiple solutions


  4. Greedy algorithms

  a. We take the best we can without worrying about the future consequences.
  b. we hope that by choosing a local optimum solution at each step we end up at a global optimum solution.



  work well for optimization problems.
also provides the best soln among multiple solutions

It works in phases. At each phase we take the best we can without worrying about the future consequences
We hope that by choosing a local optimum solution at each step we will end up global optimum solution


5.  Brute Force algorithms

a. It simply tries all possibilities until a satisfactory solution is found.

For instance :
Finding the best path between two location.

6. Randomized Algo.

a. Use a random number at least once during the computation to make decision.

we will see that quick sort algo works based on the random number to choose pivot no. and make decision about it.

RECURSION :


what is RECURSION?
Why do we need recursion?
The Logic Behind RECURSION
recursive v/s iterative solutions
How to write recursions in 3 steps
Find fibonacci series using recursion

Recursion - A way of solving problem by having a function calling itself.

It is method of solving a problem where the solution depends on the solutions to the smaller instance of the same problem.

Such problems can generally be solved by iteration as well.


Real life example can be Russian Nesting Doll 

So at first you just see one figure usually painted wood.

If you remove the top half of these first doll, you will see another slightly smaller Russian doll inside it.
It's just one piece which cannot be opened.

Sequence of similar dolls inside each other that can be opened, but everytime the size gets smaller , each time you open a doll, a smaller version
of doll will be inside and you repeat the process until you reach the final doll that cannot be open. 

So if you think of this big doll as a problem, you can see that the problem gets smaller and smaller instance of the same problem until we solve it.

- Peforming the same operation multiple times 
- In every steps we try smaller inputs to make the problem smaller.
- Base condition is needed to stop teh recursion, otherwise infinite loop will occur.

Everytime we make the problem smaller, it makes it easier to find the solution at the end.

Base condition is the condition after that we will not do anymore recursion we will stop recursion because we either will have found the answer
 or answer doesn't exists 


 e.g 

 static void openRussianDoll(int doll)
 {
    if(doll == 1)
      System.out.println("All dolls are opened");
    else
      openRussianDoll(doll - 1);
 }

Why do we need recursion?

1. Recursive thinking is really important in programming and it helps you to break down big problems into smaller ones and easier to use.

 It depends on the situation what to choose recursion or iteration

 When to choose recursion 
