# Homework 04: Doubly Linked List

Name: Chengyi Li

Github Account name: lidudu810

How many hours did it take you to complete this assignment (estimate)? 6hr

Did you collaborate with any other students/TAs/Professors? If so, tell us who and in what capacity.  
- one per row, add more if needed
Student: Zhanpeng Tong

Did you use any external resources (you do not have to cite in class material)? (Cite them below)  
- one row per resource
none

(Optional) What was your favorite part of the assignment? 

(Optional) How would you improve the assignment? 

## Understanding Time Complexity

1. Using a markdown table and markdown/latex math, show the BigO for Arrays, Singly Linked Lists, Doubly Linked Lists (so total of 3). For the columns, you will look at the Worst Case Time Complexity for Access, Search/Find,	Insertion, and Deletion.

|Big $O$ | Arrays | Singly Linked Lists | Doubly Linked Lists |
| ------ | ------ | ------------------- | ------------------- |
| Access  | $O(1)$ |	    $O(n)$	       |       $O(n)$        |
| Search  |	$O(n)$ |      $O(n)$	       |       $O(n)$        |
| Insertion| $O(n)$ |      $O(1)$	       |       $O(1)$        |
| Deletion	| $O(n)$ |	    $O(1)$	       |       $O(1)$        |

2. Usually for singly and doubly linked lists, we reference both the head and tail for speed considerations. What would be the cost if you only had your head referenced, and you wanted to push to the tail of either?  $O(?)$

Assuming that we only have access to the head reference and wish to move towards the tail, it becomes necessary to traverse the linked list from the head to the tail in order to arrive at the end node. This process involves a time complexity of $O(n)$.

3. Name an example where an array is better than a linked list, and an example where a linked list is better than an array. Make sure to reference the big O as part of your reasoning.

An example where an array is better than a linked list is when we need to access elements randomly. Arrays have constant time complexity $O(1)$ for accessing elements, while linked lists have $O(n)$ time complexity for the same operation. For example, when implementing a matrix, where we need to access individual elements using row and column indices, arrays are a better choice than linked lists.

An example where a linked list is better than an array is When we need to be insert or delete elements frequently at the head or tail of the linked list. Linked lists have constant time complexity $O(1)$ for inserting and deleting elements, while arrays have $O(n)$ time complexity for the same operations. For example, when implementing a queue, where we need to frequently add and remove elements from the front and rear ends of the queue, linked lists are a better choice than arrays. 


Note: Make sure look at your finished markdown in the browser hosted on github or via a markdown preview extension. To confirm the notation is showing up properly. 

## Important notes

* Your code **must compile and run** on the Khoury machines to earn credit. Make sure you test your programs on these machines, as this is where we grade your assignments.
* You must commit any additional files(if any) into your repository so we can test your code.
  * Points will be lost if you forget!
* Do not forget, once you have pushed your changes to your repo make sure that you **submit them to Gradescope before the assignment deadline!**

