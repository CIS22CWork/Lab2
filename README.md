# Instructions
This assignment was locked Nov 6 at 3:30pm.
<br />All the instructions related to working in Teams as explained in Lab 2 apply here.

 

<br />For this assignment, you need to implement a link-based Queue ADT.  If you finished Lab 2 with proper abstraction, you should be able to reuse most of your code in this lab.  To complete this, you will need the following:

 

<br />A Node ADT which will have two attributes - a data attribute and a pointer attribute.  Remember the Node has to be an ADT, so that it can hold any kind of data.
<br />You can choose to use this node as both a data and a head-pointing node or as a simple data node in which case you will need a new head pointing node.  In the head-pointing node, you will need to implement both front and rear pointers.
<br />A Singly Linked List ADT which will be composed of one or more of your nodes.  Implement the most common linked-list behaviors as explained in class - new list, add anywhere, delete anywhere, find anywhere, count of items in the list, empty the list, etc.
<br />Finally, implement a Queue ADT based on your singly linked list which will implement the most common Queue operations like enqueue, dequeue, front, rear, empty etc.
<br />Ensure that your Node, List and Queue ADTs are mimimal and cohesive with adequate walls around them.  Define interfaces as needed, so you can reuse them in all your subsequent assignments.
<br />Then write a main that will demonstrate the capabilities of you Queue ADT with different types of data - numbers, strings and your currency objects.
<br /> 
<br />
<br />Grading:
<br />
<br />3 points - EXE works without a hitch
<br />2 points - MSVC project structure, code styling, commenting
<br />3 points - Queue template which only exposes Queue related behaviors.
<br />2 points - Demonstration of Queue ADT in main.
 

<br />As already explained, this assignment should be done in Visual Studio or properly changed into a Visual Studio format before submitting.  Include your entire VS folder structure zipped as attachment to this question.  The exe should work on its own before the coding will be graded.  Also, include screenshots of the output.  Remember to name your project and zip file name as QueueADT_initial_1_initial2.  Add the team member names in the response box of the question for the answer to be accepted.

# Outcome
-2 using inline definitions in template methods despite warnings
<br />Other things noted but no penalty:
<br />a. Your VS code structure is non-standard
<br />b. Your implementation of stack using push_back is counter intuitive and it shows up in the UI when you print the stack as the stack grows downward, instead of upward.