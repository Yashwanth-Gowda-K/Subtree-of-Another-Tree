# Subtree-of-Another-Tree


🚀 Solution Overview
**Approach**: Recursive DFS traversal with subtree comparison.  
**Time Complexity**: O(m×n) (where `m` and `n` are nodes in `root` and `subRoot`).  
**Space Complexity**: O(min(m, n)) (recursion stack depth).

### Key Steps:
1. **Base Checks**: Handle empty tree edge cases.
2. **Tree Matching**: Compare nodes recursively.
3. **Subtree Search**: Traverse `root` to find `subRoot`.
