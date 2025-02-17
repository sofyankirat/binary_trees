Project Name
0x1D. C - Binary trees

Author's Details
Name: Wendy Munyasi.

Email: wendymunyasi@gmail.com

Tel: +254707240068.

Requirements
Allowed editors: vi, vim, emacs.
All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89.
Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl.
All your files should end with a new line.
You are not allowed to use global variables.
No more than 5 functions per file.
You are allowed to use the standard library.
The main.c files are used to test your functions, but you don’t have to push them to your repo.
The prototypes of all your functions should be included in your header file called binary_trees.h.
All your header files should be include guarded.
More Info
Please use the following data structures and types for binary trees for this project:
Basic Binary Tree

/**
 * struct binary_tree_s - Binary tree node
 *
 * @n: Integer stored in the node
 * @parent: Pointer to the parent node
 * @left: Pointer to the left child node
 * @right: Pointer to the right child node
 */
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;
Binary Search Tree

typedef struct binary_tree_s bst_t;
AVL Tree

typedef struct binary_tree_s avl_t;
Max Binary Heap

typedef struct binary_tree_s heap_t;
Project Description
Learn about what is a binary tree. What is the difference between a binary tree and a Binary Search Tree. What is the possible gain in terms of time complexity compared to linked lists. What are the depth, the height, the size of a binary tree. What are the different traversal methods to go through a binary tree. What is a complete, a full, a perfect, a balanced binary tree.

0. New node - Write a function that creates a binary tree node. - 0-binary_tree_node.c.
1. Insert left - Write a function that inserts a node as the left-child of another node. - 1-binary_tree_insert_left.c.
2. Insert right - Write a function that inserts a node as the right-child of another node. - 2-binary_tree_insert_right.c.
3. Delete - Write a function that deletes an entire binary tree. - 3-binary_tree_delete.c.
4. Is leaf - Write a function that checks if a node is a leaf. - 4-binary_tree_is_leaf.c.
5. Is root - Write a function that checks if a given node is a root. - 5-binary_tree_is_root.c.
6. Pre-order traversal - Write a function that goes through a binary tree using pre-order traversal. - 6-binary_tree_preorder.c.
7. In-order traversal - Write a function that goes through a binary tree using in-order traversal. - 100-sorted_hash_table.c.
8. Post-order traversal - Write a function that goes through a binary tree using post-order traversal. - 8-binary_tree_postorder.c.
9. Height - Write a function that measures the height of a binary tree. - 9-binary_tree_height.c.
10. Depth - Write a function that measures the depth of a node in a binary tree. - 10-binary_tree_depth.c.
11. Size - Write a function that measures the size of a binary tree. - 11-binary_tree_size.c.
12. Leaves - Write a function that counts the leaves in a binary tree. - 12-binary_tree_leaves.c.
13. Nodes - Write a function that counts the nodes with at least 1 child in a binary tree. - 13-binary_tree_nodes.c.
14. Balance factor - Write a function that measures the balance factor of a binary tree. - 14-binary_tree_balance.c.
15. Is full - Write a function that checks if a binary tree is full. - 15-binary_tree_is_full.c.
16. Is perfect - Write a function that checks if a binary tree is perfect. - 16-binary_tree_is_perfect.c.
17. Sibling - Write a function that finds the sibling of a node. - 17-binary_tree_sibling.c.
18. Uncle - Write a function that finds the uncle of a node. - 18-binary_tree_uncle.c.
19. Lowest common ancestor - Write a function that finds the lowest common ancestor of two nodes. - 100-binary_trees_ancestor.c.
20. Level-order traversal - Write a function that goes through a binary tree using level-order traversal. - 101-binary_tree_levelorder.c.
21. Is complete - Write a function that checks if a binary tree is complete. - 102-binary_tree_is_complete.c.
22. Rotate left - Write a function that performs a left-rotation on a binary tree. - 103-binary_tree_rotate_left.c.
23. Rotate right - Write a function that performs a right-rotation on a binary tree. - 104-binary_tree_rotate_right.c.
24. Is BST - Write a function that checks if a binary tree is a valid Binary Search Tree. - 110-binary_tree_is_bst.c.
25. BST - Insert - Write a function that inserts a value in a Binary Search Tree. - 111-bst_insert.c, 0-binary_tree_node.c.
26. BST - Array to BST - Write a function that goes through a binary tree using in-order traversal. -  112-array_to_bst.c, 111-bst_insert.c, 0-binary_tree_node.c.
27. BST - Search - Write a function that searches for a value in a Binary Search Tree. - 113-bst_search.c.
28. BST - Remove - Write a function that removes a node from a Binary Search Tree. - 114-bst_remove.c.
29. Big O #BST - What are the average time complexities of those operations on a Binary Search Tree (one answer per line). - 115-O.
30. Is AVL - Write a function that checks if a binary tree is a valid AVL Tree. - 120-binary_tree_is_avl.c.
31. AVL - Insert - Write a function that inserts a value in an AVL Tree. - 121-avl_insert.c, 14-binary_tree_balance.c, 103-binary_tree_rotate_left.c, 104-binary_tree_rotate_right.c, 0-binary_tree_node.c.
32. AVL - Array to AVL - Write a function that builds an AVL tree from an array. - 122-array_to_avl.c, 121-avl_insert.c, 0-binary_tree_node.c, 103-binary_tree_rotate_left.c, 104-binary_tree_rotate_right.c, 14-binary_tree_balance.c.
33. AVL - Remove - Write a function that removes a node from an AVL tree. - 123-avl_remove.c, 14-binary_tree_balance.c, 103-binary_tree_rotate_left.c, 104-binary_tree_rotate_right.c.
34. AVL - From sorted array - Write a function that builds an AVL tree from an array. - 124-sorted_array_to_avl.c, 0-binary_tree_node.c.
35. Big O #AVL Tree - What are the average time complexities of those operations on an AVL Tree (one answer per line). - 125-O.
36. Is Binary heap - Write a function that checks if a binary tree is a valid Max Binary Heap. - 130-binary_tree_is_heap.c.
37. Heap - Insert - Write a function that inserts a value in Max Binary Heap. - 131-heap_insert.c, 0-binary_tree_node.c.
38. Heap - Array to Binary Heap - Write a function that builds a Max Binary Heap tree from an array. - 132-array_to_heap.c, 131-heap_insert.c, 0-binary_tree_node.c.
39. Heap - Extract - Write a function that extracts the root node of a Max Binary Heap. - 133-heap_extract.c.
40. Heap - Sort - Write a function that converts a Binary Max Heap to a sorted array of integers. - 134-heap_to_sorted_array.c, 133-heap_extract.c.
41. Big O #Binary Heap - What are the average time complexities of those operations on a Binary Heap (one answer per line). - 135-O.
