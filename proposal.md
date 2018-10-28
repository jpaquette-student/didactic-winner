# X-Team 59 Project Proposal: The Off-Campus Housing Sorter

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

Briefly describe a problem that your team would like to solve.  
Describe at a high level a program that could solve that problem.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)  
Title: The Off-Campus Housing Sorter


2. Output: Describe the output your program will produce.  Include and example format of the output produced.  
It displays off-campus housing locations sorted to match the wants of the users. For example, if a user wanted to live
close to a certain area they could select that area and the program would display locations nearest to that area. The program
also displays locations based on a variety of properties such as price, room sizes, etc.  

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.  
Housing data. These would be properties about various locations such as number of bedrooms, bathrooms,
size, price, etc. The user would input preferences in order to change how the data is sorted and displayed to them.

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.  
See Figure 1  
![Figure 1](https://github.com/jpaquette-student/didactic-winner/blob/master/dALXHQL%20-%20Imgur.jpg)

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.  
Red-Black Trees, House Nodes, UI Display, Main class to run program


Name each interface or class and briefly describe its function or purpose.  
Red-Black Tree Interface: This would serve as the interface to implement for a sorted red-black tree  
Red-Black Tree: Store the locations sorted based on one (or more) property of the locations 
House Nodes: Store the information of a location and represents the location in a tree
UI: Would display the user interface and take in input from the user  
Main: Running the calculations/making decisions. Take input from UI, manipulate red-black trees based on preferences, and decide which tree to display in UI. Would also calculate the distance from user click to locations and include this as a user preference as well.

6. Comprehensive testing for each unit  
Red-Black Tree: Check that the red-black tree properties hold. Check whether all the locations that fit the user's selection are involved and correctly sorted. Check to see the preferences match the tree's configuration.
Housing Nodes: Test to see if the house's info is up to date.  
UI: Test each item on the interface can be edited by the user and valid input options are displayed. Test that the outputted list correctly displays (order, correct info, etc)  
Main: Test edge cases for preferences, and that the red-black tree functions work as expected


## Edit and Submit this file and any figures referenced by this document.

