# Fund and Relief distribution system

# Introduction:
  This GitHub project is an implementation of a fund and relief distribution system in C, allowing users to log in as either an admin or a consumer. The system 
  stores user information in files and uses data structures like structures to manage user data. The code consists of user-defined functions to facilitate         
  registration and login processes.

# Process:
  The program starts with a interface where the observer is asked whether he wants to do here. 

# User-Defined Functions:

 1.void registerUser(struct User users[], int *userCount): 
   Registers a new user by collecting their personal information and saving it both in memory and in a file for future access.

 2.int findUserByName(struct User users[], int userCount, const char *name, const char *pass, const char *city): 
   Searches for a user by their name, password, and city in the stored user data. Returns the index of the user if found or various error codes if not.

# Features:

 Admin Panel: 
   The system includes an admin panel accessible with a unique ID and password. Admins can manage fund distribution and check the current fund amount.

 Consumer Registration and Login: 
   Consumers can register with their name, age, address, and other information. Registered users can log in using their credentials.
 
 City-Based Access: 
   The system allows access based on the city, ensuring that users can only access data related to their respective cities.

# Hindrances of the Distribution System:

  1.User Limit: 
    The system currently has a hard-coded maximum user limit (MAX_USERS), which might not be scalable for larger communities.

  2.Limited Security: 
    The password handling is basic, and the code does not include security features like encryption, making it vulnerable to attacks.

# Future Upgrades:
 To upgrade the distribution system, consider the following improvements:

  1.Dynamic User Management: 
    Implement dynamic memory allocation to handle a growing number of users effectively.

  2.Enhanced Security: 
    Add password hashing and other security measures to protect user data.

  3.Optimized Fund Distribution: 
    Improve the fund distribution algorithm to ensure fair and efficient resource allocation.

  4.User-Friendly Interface: 
    Create a user-friendly command-line interface or develop a graphical user interface (GUI) for better usability.

# Conclusion:
  This GitHub project presents a fund and relief distribution system in C, providing both registration and login options for users. It uses files and structures 
  to manage user data and includes an admin panel for fund management. However, the system has limitations in terms of scalability, security, and efficiency that 
  need to be addressed in future upgrades. This project lays the foundation for a potentially impactful and accessible system to aid those in need.
