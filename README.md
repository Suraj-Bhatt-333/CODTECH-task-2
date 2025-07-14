# LINKED LIST IMPLEMENTATION
*COMPANY*: CODTECH IT SOLUTIONS  
*NAME*: SURAJ BHATT  
*INTERN ID*: CT04DH722  
*DOMAIN*: C LANGUAGE  
*DURATION*: 4 WEEKS( 29/6/25-29/7/25)  
*MENTOR*: NEELA SANTHOSH KUMAR  
DESCRIPTION OF THE PROJECT:  

The second task of my internship involved implementing a singly linked list in C with functionalities for insertion, deletion, and traversal. I used Visual Studio Code and GCC as before, ensuring that my environment was ready and consistent with Task 1. I created a new file named linked_list.c and started by defining the basic structure of a node using a struct in C.

The struct Node contained an integer data field and a pointer to the next node. I initialized the head pointer to NULL and developed a menu-driven interface for the user. The user could insert a new node at the end, delete a node by value, and display the current list. For insertion, I dynamically allocated memory using malloc() for the new node. If the list was empty, the head would point to this new node. Otherwise, I traversed the list until the last node and added the new node at the end.

Next, I moved to the deletion functionality. This part was more complex, as it required handling multiple cases: deleting the head node, deleting a middle or last node, and trying to delete a non-existent node. I used a combination of if-else conditions and pointer manipulation to ensure correctness. After deletion, I used free() to release the memory. I also handled edge cases such as trying to delete from an empty list or attempting to delete a node that does not exist.

Traversal was straightforward. I iterated through the list using a temporary pointer and printed each node’s data. I included messages when the list was empty to improve user experience. This made the interface friendlier, especially for users who were unfamiliar with linked list behavior.

To ensure robustness, I tested each function thoroughly in the terminal and also simulated user input. The debugging process included adding printf() statements to trace pointer behavior and ensure correct link adjustments. I paid close attention to pointer manipulation and memory allocation to avoid segmentation faults and memory leaks.

I organized my code using separate functions for insertion, deletion, and traversal. I also included a loop to keep the menu running until the user decided to exit. I maintained clean code practices, added inline comments, and committed the code to a new GitHub repository with a detailed README explaining compilation and execution. I ensured that each function was tested in isolation and in combination to guarantee reliability.

Through this task, I learned how to manage dynamic memory, use pointers more efficiently, and structure linked list operations cleanly. It also reinforced important concepts of memory management in C and gave me confidence in building basic data structures from scratch. Most importantly, it made me realize how fundamental data structures like linked lists form the backbone of more advanced computer science topics. This task was not just a coding exercise but a deep dive into how memory and data are managed at a low level in C.

# OUTPUT:  
<img width="1919" height="998" alt="Image" src="https://github.com/user-attachments/assets/efe86fdb-e054-408f-b23b-c7d11ba1b3b9" />
