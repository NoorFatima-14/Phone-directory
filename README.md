# 📞 Phone Directory 

## Project Overview
The **Phone Directory System** is a console-based application developed as part of the **Data Structures and Algorithms (DSA)** course. It allows users to efficiently manage contacts with features such as adding, searching, deleting, and displaying contacts. The system supports multiple phone numbers per contact while ensuring no duplication, leveraging optimized data structures for enhanced performance.

## Key Features
- **Add Contact**: Save contact information, including multiple unique phone numbers.
- **Search Contact**: Retrieve a contact's details by name.
- **Remove Contact**: Delete a contact and all associated phone numbers.
- **Display All Contacts**: View all stored contacts in alphabetical order.

## Data Structures
### Binary Search Tree (BST)
- **Efficient Operations**: The **BST** is used for storing and organizing contacts, allowing quick searches, insertions, and deletions with an average time complexity of **O(log n)**.
- **Sorted Data**: Contacts are stored in sorted order based on names, facilitating easy traversal.

### Set
- **Phone Number Management**: The **Set** data structure is used to store multiple phone numbers per contact, ensuring uniqueness and preventing duplicates.

## Project Requirements
### Functional:
- Save and manage contact information.
- Support operations for adding, searching, deleting, and displaying contacts.
- Allow storing multiple phone numbers per contact without duplication.

### Non-Functional:
- **Performance**: Efficient in both time and space.
- **Usability**: Simple and user-friendly command-line interface.

## Complexity Analysis
- **BST Operations**: Average time complexity of **O(log n)** for insertion, deletion, and search. Worst-case time complexity of **O(n)** in unbalanced scenarios.
- **Set Operations**: Time complexity of **O(n)** for insertion and search, ensuring uniqueness of phone numbers.

## Technologies Used
- **C++**: Language used for implementation.
- **Binary Search Tree (BST)**: For efficient contact management.
- **Set**: For managing unique phone numbers.

