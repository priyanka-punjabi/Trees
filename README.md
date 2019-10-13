BINARY TREE

I. PROPERTIES

	1. Level
		Level of a root = 1
		Maximum no. of nodes at any level = 2^(level - 1)
    
         # Since every node in binary tree can have atmost 2 child nodes
		If no. of nodes at level l = 2^(l - 1), 
              then no. of nodes at next level = 2 * 2^(l - 1)
    
    2. Height
		Height of a tree with 1 node (root) = 1
		Maximum no. of nodes in a binary tree of height h = 2^(h) - 1
		If height of tree starts with 0, then max no. of nodes = 2^(h + 1) - 1
    
	3. For a BT with N nodes, minimum height or level = Log(N + 1)
		If height starts with 0, then minimum height = Log(N + 1) - 1

	4. A BT with L leaves has at least Log (L) + 1 levels

	5. In a BT, the number of leave nodes = T + 1
		where T = no. of internal nodes with 2 children
