# Lab-1_202001461

# Q-1

## Library Information System

### Functional Requirements :
1. Allow members to borrow/return books.
2. Allow members to extend the date of borrowing if no booking for the same book is made.
3. Allow only librarian to add/remove books.
4. Allow users(including non-members) to search/browse books by name,publication date,author.
5. System should notify the user and librarian about the overdue books.
6. System should calculate late fine upon return of the book.
7. Don't allow members to issue more than 3 books at a time and 10 books in the course of 6 months. 

### Non-functional Requirements :
1. Usability : A library management system's primary non-functional requirement is usability. Everyone should be able to grasp the UI and find the necessary information                without the need for any specialised training. Depending on the needs, other languages can be given.
2. Ease of Use : The system should be user-friendly and should provide intuitive Graphical User Interface (GUI).
3. Reliability : The Server should carry out required tasks as desired. The system should complete its tasks accurately, such as user registration, user validation, and                  authorization, book search and issue functionality, return status, and database updating via database and application synchronisation.
4. Security : The system must be secure in terms of handling user data, even inside the institute, the user data should be effectively encrypted and verified.
5. Scalability : The system should be scalable to support extended number of users.
6. Efficiency and maintainablity : The system should be efficient and maintainable.The administartor should be able to extend the system without harming the running                                        application.The software must be portable.

### Actors :
1. User - Logging in enables the user to see the catalogue, do a book search, check out, reserve, renew, and return a book.
2. Librarian - The librarian can add new members, add and update the library's collection of books, collect overdue fines, and issue books.
3. System - The system itself. It keeps track of the borrowed books and sends notifications to the librarian and users about the overdue books.



# Q-2 

## Hearing aid 

### Functional Requirements :
1. The application should have notifications/pop-ups for notifying the user about critical conditions related to safety such as car honking,baby crying etc.
2. The application must have a clear distiction between notifications from other apps for user to easily identify it.i.e. In form of flash / different sounds.
3. The application should be able to schedule time intervals for the aiding device to start/stop.e.g. For older patients, it might be difficult to use application.
4. The application should allow the user to control sound levels.

### Non-functional Requirements :
1. Intuitiveness : The application should be intutive enough with simple GUI.
2. Maintainability : The application should be maintainable and easily modifiable without affecting the current functionalities.
3. Accuracy : The application must be accurate to show the status of the device, to start/stop device at set time intervals. 
4. Latency : The application should be faster in terms of interacting with aiding device.
5. Effiecincy : The application should not take up too much space and utilise system resources efficiently.


### Actors :
1. User : The user will be able to control the hearing aid using application.
2. Hearing aid : Hearing aid will get instructions from application and will send alerts/notifications to it back. 
