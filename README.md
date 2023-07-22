# Bank-Management-System
The provided C++ code implements a comprehensive banking system that manages customer accounts, passwords, and various banking operations. It consists of classes for a Binary Search Tree (BST) and a Hashtable, each serving a specific purpose in the banking application.

Binary Search Tree (BST):
The BST class handles the storage and management of customer account information. It enables the addition of new accounts and deletion of existing accounts. The class also supports searching for specific accounts based on their account numbers. Additionally, it allows updating account details such as name, address, and account balance.

Hashtable:
The Hashtable class is utilized for secure password storage. It implements separate chaining to handle potential collisions. The class enables the addition of new passwords and verification of password matches for specific accounts. It also provides functionality to display all stored passwords and delete passwords associated with deleted accounts.

Node and Node_1:
These classes define bidirectional nodes used in the implementation of the BST and Hashtable, respectively. The Node class has pointers to the next and previous nodes, while the Node_1 class contains information about account numbers, passwords, and pointers to the next node within a linked list.

The code further distinguishes user roles into admin, customer, and staff, offering different functionalities to each:

Admin Role:
The admin() function allows administrators to perform tasks such as adding and deleting accounts, viewing all accounts, viewing account passwords, and editing account information.

Customer Role:
The customer() function enables customers to view their account details and transaction history.

Staff Role:
The staff() function caters to staff members who can view transaction history, transfer funds between accounts, withdraw money, and deposit money.

The code exhibits advanced proficiency in data structures like Binary Search Trees and Hashtables. It also demonstrates a strong grasp of object-oriented programming concepts, file handling for data persistence, and role-based access control implementation for a secure and efficient banking system. The comprehensive nature of this code showcases the ability to design and develop complex applications using C++.
