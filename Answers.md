1. Why does inorder traversal of a BST return elements in sorted order?
   becuase in a BST every left child is smaller than the node and the right child is larger.
   inorder visits left -> node -> right so smallest to largest. 

2. Give an example of an insertion order that produces a highly unbalanced BST. What does the inorder traversal look like for that tree?
   insertion order: 1, 2, 3, 4, 5
   inorder traversal: 1, 2, 3, 4, 5

3. In your own words, explain the differences between: Recursive vs iterative traversal and Depth-first vs breadth-first traversal.
   recursive: the call stack, simpler to write and cleaner visually.
   iteravite: uses your own stack, queue. more control and avoids deep recursion.

   DFS: goes as deep as possible before backtracking. preorder, inorder, postorder
   BFS: visits nodes level by level from top to bottom.

4. When might you prefer a breadth-first traversal in a real application?
   when you need to process nodes by layers. ex finding the shortest path. check levels or exploring items in the order of thier 'distance' from the root. 
