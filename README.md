# WhatBytes_assignment

## Technologies Used
- **Django:** The backend framework used for handling authentication, routing, and rendering templates.
- **Tailwind CSS:** Used for styling the frontend to create a responsive and modern user interface.
- **SQLite:** The default database used for development purposes.


## Implementation Choices
- Django's built-in authentication system was used for user registration, login, and logout functionality.
### Profile Page:
- The profile page displays the user's basic information, such as username, email, date joined, and last login.
  
  ![image](https://github.com/user-attachments/assets/dc10d8a6-eee1-43f4-80d9-1e8995c73506)

### Password Change:
- Django's `PasswordChangeForm` was used to handle password changes securely.

- After a successful password change, the user's session is updated using `update_session_auth_hash` to keep them logged in.
![image](https://github.com/user-attachments/assets/b1bd671e-03fc-4aa7-8b76-4d6587e40bbb)

## Demonstrate video:


https://github.com/user-attachments/assets/34472a58-5b4e-46ed-9775-a6ae3a82c5f8

