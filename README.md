# Updated-BinarySearchTree
Binary Search Tree implementation in Python.
This is an implementation of a Binary Search Tree (BST) in Python. It provides operations for creating a BST, adding nodes, removing nodes, searching for a specific value, traversing the tree in different orders (preorder, inorder, postorder, level order), getting the height and number of nodes in the tree, and serializing/deserializing the tree.

# Usage
You can use this implementation by following the example below:

```
#Create a BinarySearchTree object
bst = BinarySearchTree()

#Add nodes to the tree 
bst.add(5)
bst.add(3)
bst.add(7)
bst.add(2)
bst.add(4)
bst.add(6)
bst.add(8)

#Perform operations on the tree 
print("Height:", bst.getHeight())
print("Number of nodes:", bst.getNumberOfNodes())
print("Preorder traversal:", bst.preorder())
print("Inorder traversal:", bst.inorder())
print("Postorder traversal:", bst.postorder())
print("Level-order traversal:", bst.levelorder())

#Remove a node from the tree
bst.remove(7)

#Serialize the tree to a file
bst.serialize('tree.txt')

#Deserialize a tree from a file
new_tree = BinarySearchTree.deserialize('tree.txt')

#Perform operations on the new tree
print("Height of new tree:", new_tree.getHeight())
print("Number of nodes in new tree:", new_tree.getNumberOfNodes())
```
# Contributing
If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request. Your contributions are welcome!

# License
This project is licensed under the MIT License - see the LICENSE file for details.

# References
Binary Search Tree - Wikipedia  
Binary Search Tree - GeeksforGeeks  
Data Abstraction & Problem Solving with Walls And Mirrors - Frank M. Carrano, Timothy M. Henry  

# Author
Manukyan Sasha - https://github.com/ManukyanSash
