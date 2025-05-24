# CS2420-8.1-P8-Binary-Search-Tree-solved

Download Here: [CS2420 8.1 P8 Binary Search Tree solved](https://jarviscodinghub.com/assignment/8-1-p8-binary-search-tree-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Project 8 Binary Search Tree
Purpose
This project will give you experience with Binary Search Trees You will build upon this proect with the next project so be sure you
document your code well and understand well how works.
Implement the two classes defined in the following UML diagrams.
BinarySearch Tree
void
-Inser1heoencursorNoæ•. dataMV_ Node•
•Search(data-intr No&’
•SearcnHeperurscg:Node•. dat&nt): Noe•
vod
•RemoveHelper(tursorNode•,
-InorærTraversa10:
void
_ . cursorNoæ•): void
NØe•
Node•
-needed ForUntTest Observe
•Nocedats:nt lencndNode•.
•lsLeat().
+1JpOateHeont() vod
You need to implement these two UML diagrams in:
• Node.h
• Node.cpp
• BinarySearchTree.h
• BinarySearchTree.cpp
Recursion
The following functions in dinarySearchTree MUST be implemented using recursion (their recursive •helper” functions are specified in the
UML diagram):
• Insert
• Search
• Remove
• InorderTraveral
• Print
• Size
Unit Testing
ZyLabs will be auto-grading this project.
The Node and BinarySearchTree classes must be implemented EXACTLY as shown in the above UML diagrams
Main.cpp MUST include “Observerh• and • Recursicncounter.h• near the beginning of the file.
Main.cpp MUST define the following four static variables for these two classes as shown below:
include”BinarySearchTree.h”
include”Observer.h”
include”RecursionCounter.h”

// needed for Unit Testing. DO NOT REMOVE
intObserver.:numDestructions 0;
intRecursionCounter.maxDepth O;
int mainO
Also. 10 assist the Unit Testing portion or ZyLabs, the Node class MUST have a private variable of type •Observer’. This means that Node.h
must *include •Observer_h” at the top of the file. i.e.:
include”Observer.h”
classNode
public:
// your code goes here
private:
Observer neededForUnitTest;
// do not remove
To allow the unit Test to verify that recursicn is properly being used. one local variable of type RecursionCounter needs to be declared at the
beginning of EACH” Recursive •Helper’ furction”. For example
intBinarySearchTree::SizeHeIper(Node cursor)
RecursionCounter neededFor’JnitTest;
// base case
Main Driver
// MUST BE HERE
In Main.cpp implement the function mainO which creates a BinarySearchTree object and performs tre following:
T Insert the following dala into your tree:
3 Perform an In-order traversal of the tree
4 print tree
5 Remove the following data from the tree
7. Print the tree
a Perform an In-order traversal of the tree
The output should look like:

28, 30
21 (4)
10,
[ Empty]
14,
15,
18,
21,
26,
3 (0) [leaf]
7 (e) [leaf]
14 (2)
10 (e) [leaf]
18 (1)
15 (B) [leaf]
[Empty]
26 (2)
[ Empty ]
28 (e) [leaf]
[Empty]
26 (3)
lø (2)
[Empty]
3 (e) [leaf]
14 (0) [leaf]
3ø (1)
28 (0) [leaf]
2,
[ Empty ]
10, 14, 26,
28,
30,
