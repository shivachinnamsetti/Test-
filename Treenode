class TreeNode:
    def _init_(self, val=0, left=None, right=None):

        self.val = val

        self.left = left

        self.right = right
def max_depth(root):

    if root is None:
        return 0

    else:

        left_depth = max_depth(root.left)
        right_depth = max_depth(root.right)
        return max(left_depth, right_depth) + 1
root = TreeNode(3)
root.left = TreeNode(9)
root.right = TreeNode(20)
root.right.left = TreeNode(15)
root.right.right = TreeNode(7)
print("Maximum depth of the binary tree:", max_depth(root)
