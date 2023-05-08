
This is a C program for a people registration system that allows the user to input, modify, delete, and search for information stored in arrays. Here are the main parts of the code:

-The program starts with the definition of some constants and the declaration of arrays to store information about the registrations (names, phone numbers, zip codes, and registration numbers).
The function "cadastro()" is defined, which contains the main logic of the program. This function has a static variable "linha" used to control the number of registrations.
The "main()" function calls the "cadastro()" function to execute the program.
The "cadastro()" function displays a menu of options for the user to choose what to do (register, modify, delete or search). The program uses a "do-while" loop to allow the user to create multiple registrations by choosing option "1".
-Option "2" allows the user to modify registration data, displaying the registration form again.
-Option "3" allows the user to delete a registration based on the registration number. To do this, the program prompts the user for the registration number and then loops through the registration number array to find the match. If a match is found, the values of the phone numbers and zip codes will be changed to zero.
-Option "4" allows the user to search for information about an existing registration based on the registration number. The program prompts the user for the registration number and then loops through the registration number array to find the match. If a match is found, the values of the names, phone numbers, zip codes, and registration numbers will be displayed. The program offers the option to continue searching or go back to the main menu.
When the user chooses option "0", the program ends and returns 0.
