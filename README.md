Iterator: `struct bst_iterator` iterator that returns values from a BST in the same order they would be visited in an in-order traversal of the tree.

Functions:

`bst_height()` determines the height of a given BST.  
`bst_path sum()` determines whether a BST contains any path from the root to a leaf in which the values of the nodes sum to a specified value.
`bst_iterator_create()` - allocates and initializes an iterator for a given BST
`bst_iterator_free()` - frees all memory allocated to a BST iterator
`bst_iterator_has_next()` - tells the user whether there are more values in the BST to which to iterate
`bst_iterator_next()` - returns the next value in the in-order iteration of the BST