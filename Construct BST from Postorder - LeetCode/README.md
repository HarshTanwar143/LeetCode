# Construct BST from Postorder
## Easy
We know this problem is a piece of cake for you. Challenge yourself with GfG Weekly Contest 

banner
Given postorder traversal of a Binary Search Tree, you need to construct a BST from postorder traversal. The output will be inorder traversal of the constructed BST.

 

Example 1:

Input:
6
1 7 5 50 40 10

Output:
1 5 7 10 40 50

Explanation:
Testcase 1: The BST for the given post order traversal is:


Thus the inorder traversal of BST is: 1 5 7 10 40 50.
 

Your Task:
The task is to complete the function constructTree() which takes an array post[], size as as the argument and returns the root of BST.

 

Expected Time Complexity: O(No. of  nodes in BST)
Expected Auxiliary Space: O(No. of  nodes in BST)

 

Constraints:
1 <= T <= 100
1 <= N <= 200
