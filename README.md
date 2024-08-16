# security_system
Certainly! Here’s the translated text:

---

Initially, I wanted to name the app "home_security," but as I was developing it, that name no longer made sense, so I changed it to "security app." However, I think the new name might not be visible everywhere.

The application manages a database consisting of individuals who have access to the company.

Currently, access to the application is restricted to one person (for now), and they can log in using their username and password. On the login screen, I have set it up so that users cannot move to the next text box until the previous one is filled, and navigation can be done using the down arrow key and Enter. I would also like to add the ability to navigate backward using the up arrow key, and allow users to make up to three mistakes before locking them out from further login attempts.

Once the user logs in, a second window opens where they can access the database, add a new user, delete a user using the UID (card UID), or delete the entire database. Here, I would also introduce a check to see if a user with the given UID already exists. Additionally, I would add navigation using the arrow keys and validation to ensure that inputs like email and UID are valid.

What I would like to try next is to integrate the application/database with an ESP32, where I would have an additional table in the database representing access history. This table would contain arrival and departure times, so that each time a card is swiped, it is logged in the database. I am also considering adding functionality to program cards through the application, such as changing UID, managing memory, and similar tasks.

---
