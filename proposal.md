# X-Team 60 Project Proposal for the Speedy Order 5000

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  

 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.

 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Brief ly describe a problem that your team would like to solve.  
Describe at a high level a program that could solve that problem.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

2. Output: Describe the output your program will produce.  Include and example format of the output produced.
The output should show the order status which includes payment status, estimated time, what your order is.
|
| Payment Status:       String  ( payment processed approved, declined or processing)
| Estimated Time:       String  ( expected wait time and estimated finish time printed in formatted string)
| Content of Order:     String  ( a visualized list of your order)
|


3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
The program would take in orders for people at a restaurant 

|                 |   User Input        |
|-----------------|---------------------|
| Table Number:   |   int or String     |
| Order:          |   String            |
| Priority:       |   int               |
| Cost:           |   double            |
| Calculated Tip: |   double            |
| Status:         |   String            |

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

We would most likely use a simple text GUI with the following screens:

 - Welcome Screen
 - Input Screen
 - Orders Screen
 - Output Screen
 - Inventory Screen

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

| Screen           | Discription                                                  |
| ---------------- | ------------------------------------------------------------ |
| Welcome Screen   | gives options, and an explanation                            |
| Input Screen     | shows input table                                            |
| Orders Screen    | shows list of orders, and their values                       |
| Output Screen    | if order is ready or priority is >1 (?) then have it appear as done or need to be done |
| Inventory Screen | list of all items in backroom, needs to be instantiated.     |

Name each interface or class and briefly describe its function or purpose.

- POS: the main class that deals with executingt he point of sale (POS) system
- TestPOS: JUnit test case class for the POS class 
- AVLTree: we need a rebalancing tree to store the customer oders
- AVLTreeADT: interface for AVL tree
- TestAVLTree: JUnit test case class for the AVLTree class
- Customer: class to be used to create cutomer objects
- CustomerADT: interface for the Customer class
- TestCustomer: JUnit test case class for the Customer class 


## Edit and Submit this file and any figures referenced by this document.

