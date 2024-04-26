# Workshop 3 - Solution

This is a workshop related with a backend system to provide a vehicles catalog using python and patterns design.

## Requirements

The requirements for this workshop are presented as follows:

- Application is still consuming a lot of memory, so you must reduce it as much as possible.
- An authentication system is needed, so you must create a simple login system where you could register user and authenticate them.
- You should differentiate two types of users: Admin and User. Admins could create, update, and delete vehicles, while Users could only see and search vehicles.
- You should log all the actions made by the users, so you could track both the changes made in the vehicle and searches performed.
- Separete your project in different subsystems, and a made a simple interface to interact with them.
- In addition, you must create a monitoring system to check the memory consumption and time execution of the searches in the application, and save stats in a _performance_log_ file.
- To increase performance, you should implement a cache system to store the last five search results over vehicles.
- Verify if you could add encapsulation to increase the security of the application.
## Business Rules

- Every vehicle just have chassis of type A or B.
- Gas consumption is based on engine information...
- Gas consumption is based on next equation. 
  `1.1 ∗ engine.potency + 0.2 ∗ engine.weight - (0.3 if A or 0.5 if B)`
