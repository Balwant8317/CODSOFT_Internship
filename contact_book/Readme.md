# Contact List
![contact_list_with_python_tkinter](https://github.com/tpauldike/rough_work/blob/main/screenshots/contact_list.png)

## About
This is a desktop app built with `Python Tkinter` for saving, viewing, updating and deleting contacts with details such as; name (compulsory), phone (compulsory), email (optional but must be valid) and adrress (optional as well).

The app was built and tested on `Ubuntu 22.04.2`

`SQLite` was used for the database

## Features
1. A beautiful user interface built with `Python`, using Tkinter as the GUI tool
2. Data validation while creating or updating contacts;
    - The Name and Phone fields cannot be empty
    - The email must be a valid one
    - Each of the four fields have maximum length of characters allowed, repectively and they cannot be exceeded
3. CRUD operations and more:
    - Create contact
    - View contacts
    - View contact details
    - Update an existing contact
    - Delete contacts
    - Page navigation and background color toggle during error display and focus on a popup widget, for a good user experience

4. Feedback when operation is successful and warnings when there's an error
