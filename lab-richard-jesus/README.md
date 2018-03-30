# General information
Author: Richard and Jesus

# App use
This an implementation of  binary search trees using javascript

## Installing
1.Clone Directory
2.CD into lab-richard-jesus
3.Run "npm i" in the terminal
4.Run node from the terminal
5.In the node REPL run the following commands

```
const BinaryTree = require('./lib/binarytree.js').BinaryTree; // imports BinaryTree Class and methods
const BST = require('./lib/bst.js').BST; // imports BST Class and methods

// Use treenode from one of the following libraries
const TreeNode = require('./lib/bst.js').TreeNode; // import TreeNode class from BST library
const TreeNode = require('./lib/binarytree.js').TreeNode; // import TreeNode class from BST library
```
## Big-O notation

For each of the following commands the Big-O notation is as follows:
```
BST.insert(TreeNode) // Big-O of O(n)
BST.find(value) // Big-O of O(n)
BinaryTree.inOrderTraversal() // Big-O of O(n)
BinaryTree.preOrderTraversal() // Big-O of O(n)
BST.remove(value) // Big-O of O(n)
TreeNode, BST, and BinaryTree constructors // O(1)
BST.isBalanced() // Big-O of O(n)
BinaryTree.postOrderTraversal() // Big-O of O(n)
```

## Running tests

Simply use the following in the terminal window to run the tests
```
npm run test
```
