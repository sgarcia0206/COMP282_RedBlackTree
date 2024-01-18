/**************************************************************************************************************************

Sergio Garcia

COMP 282 Vasikarla S.

10/28/2023

What is a Red Black Tree?


A Red-Black Tree is a type of self-balancing binary search tree, where each node in the tree contains an extra bit for denoting the color of the node, either red or black. The structure of a Red-Black Tree is maintained according to several properties that ensure balanced and efficient search, insertion, and deletion operations.

Here are the key properties of a Red-Black Tree:

Binary Search Tree Property:

Every node has at most two children: a left child and a right child.
For each node, all elements in its left subtree are less than the node's value, and all elements in its right subtree are greater than the node's value.
Color Property:

Each node is either red or black.
Root Property:

The root is always black.
Leaf Property:

Every leaf (NIL) is black.
Red Property:

If a red node has children, then the children are always black.
No two consecutive red nodes can appear on any path from the root to a leaf.
Depth Property:

For each node, any simple path from this node to any of its descendant leaves contains the same number of black nodes. This is sometimes referred to as the black height.
These properties guarantee that the Red-Black Tree remains balanced, with a logarithmic height. As a result, the search, insertion, and deletion operations have an efficient time complexity of O(log n), where n is the number of elements in the tree.

The color-coding of nodes provides a mechanism to balance the tree during insertion and deletion operations, ensuring that the tree maintains its balanced structure. The balancing properties of Red-Black Trees make them suitable for various applications where efficient search and insertion operations are crucial.

TASK

Create a Red Black Tree with insertion, deletion, search, and display/show operations

********************************************************************************************************************/
