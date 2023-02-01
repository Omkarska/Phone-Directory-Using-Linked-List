This program is a simple implementation of a phone directory using linked lists. A phone directory is a database that stores the contact information of people, including their name, phone number, and email address.

The program defines a structure named "Contact_book" which holds the information for each contact, including their phone number, name, email, and pointers to the previous and next contacts in the list. The head of the linked list is defined as a global variable.

The program provides various functionalities for the phone directory, including:

Adding a new contact to the directory
Searching for a contact by name, email, or phone number
Deleting a contact by phone number or email
Updating a contact's information by name, email, or phone number
To add a new contact, the program calls the "add_to_list" function and passes the information for the new contact as arguments. This function creates a new node, assigns the values of the new contact to the node, and adds the node to the linked list in alphabetical order based on the name.

To search for a contact, the program provides three functions: "searchByName", "searchbyEmail", and "searchbyNumber", which search for a contact by name, email, or phone number, respectively. If a match is found, the function displays the contact's information.

To delete a contact, the program provides two functions: "delbynumber" and "delbyemail", which delete a contact by phone number or email, respectively.

To update a contact's information, the program provides three functions: "updateByName", "updateByNumber", and "updateByEmail". These functions allow the user to update the information for a contact by name, email, or phone number, respectively.

The "display" function can be used to display the entire phone directory. The "updateRecord" function is used to call the appropriate update function based on the user's input.
