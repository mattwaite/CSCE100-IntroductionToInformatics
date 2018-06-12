# Problem decomposition

One of the core ideas that you are going to deal with as students of informatics and as professionals is that problems are not ever One Big Problem, but a series of much smaller problems that you solve on the way to solving the big problem.

The problem with this, so to speak, is that you must first figure out what the little problems are. Often, the goal is to make the problems so small they're trivial to solve, and that makes getting to your goal easier.

There are many methods, and they go by many names, to make this happen. Here are some simple ones:

* Recursive Decomposition: Divide the problem into subproblems, then divide the subproblems into smaller problems, and so on until the problems are simple to solve.
* Functional Decomposition: Divide the problem into a set of functions, or groups of instructions. This method allows for the functions to be performed concurrently.
* Data Decomposition: If your problem is data, data decomposition divides the data into groups where different processes or problems are solved. For example: you can divide the data into input data, intermediate data and output data.

**An example is instructive:**

You want to write a program that goes to Rate My Professors and grabs the rating for each professor at UNL for a database you're making. Without writing any code -- or knowing anything about any code -- what steps will your program have to perform in order to accomplish this task?

***Notes***

1. They'll first talk about getting the page. This is the right track, but it opens the discussion of just how granular you can get, because you can get into request/response, HTTP response code handling, etc.
2. Don't forget that the program has to read the HTML. It's not a browser.
3. Traversing the DOM, finding a place in the code.
4. Identifying patterns. And patterns within patterns.
5. What to do with the data when you find it?

**Charting**

Often, when decomposing a problem, it helps to chart out what and when something occurs. There's not really a right or wrong way to go about this, so long as it's clear what is being done when and why. A classic example is a series of connected bubbles -- a flow diagram.

![image](http://gwb.blob.core.windows.net/liammclennan/WindowsLiveWriter/InvestigatingStrategiesForFunctionalDeco_1053C/image_2.png)

**Example**

Let's decompose a math problem graphically. You are going to make a device that detects when people are texting. The micro controller costs $30 a board, the RF detector $15, the battery $10 and you'll need two batteries to keep it running long enough for it to work. You want to make $1,000 units. What is your total costs? Chart your steps.

**Homework**

Using a problem discussed in class so far, decompose it. What would the steps be? What would they look like in a flow diagram? Submit your steps and your flow diagram (hint: Word and PowerPoint both can make flow diagrams) to Blackboard.
