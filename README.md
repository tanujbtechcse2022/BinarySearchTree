# BinarySearchTree
In this I make BinarySearchTree in java language learned from cipher school
In this project, a Java Binary Search Tree (BST) is implemented. An effective data structure for insertion, deletion, and lookup that preserves sorted order is called a BST. This implementation provides methods to execute an inorder traverse, delete nodes, insert nodes, and search for values.
Features--

*Insert: Add new elements to the BST. *Search: Find elements in the BST. *Delete: Remove elements from the BST. *Inorder Traversal: Retrieve elements in sorted order.

Usage-- *Insert To insert a value into the BST:

BinarySearchTree tree = new BinarySearchTree(); tree.insert(50);

*Search To search for a value in the BST:

boolean found = tree.search(50); System.out.println(found ? "Found" : "Not Found");

*Delete To delete a value from the BST:

tree.deleteKey(50);

*Inorder Traversal To perform an inorder traversal and print the values in sorted order:

tree.inorder();

Examples-- Here are some examples of how to use the Binary Search Tree implementation:

*Example 1: Inserting and Searching

public class Main { public static void main(String[] args) { BinarySearchTree tree = new BinarySearchTree();

    // Insert values
    tree.insert(50);
    tree.insert(30);
    tree.insert(70);
    tree.insert(20);
    tree.insert(40);
    tree.insert(60);
    tree.insert(80);

    // Search for a value
    boolean found = tree.search(70);
    System.out.println(found ? "Found" : "Not Found");
}
}

*Example 2: Deleting and Inorder Traversal

public class Main { public static void main(String[] args) { BinarySearchTree tree = new BinarySearchTree();

    // Insert values
    tree.insert(50);
    tree.insert(30);
    tree.insert(70);
    tree.insert(20);
    tree.insert(40);
    tree.insert(60);
    tree.insert(80);

    // Delete a value
    tree.deleteKey(50);

    // Perform inorder traversal
    System.out.println("Inorder traversal:");
    tree.inorder();
}
}

/* Let us create following BST 50 /
30 70 / \ /
20 40 60 80 */
