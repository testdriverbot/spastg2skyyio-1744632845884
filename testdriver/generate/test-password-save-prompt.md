1. /run testdriver/login.yml --embed
2. Observe the "Save password?" dialog.
3. Click "Save" to store the password.
4. Assert that a confirmation prompt for saving the password is shown.
5. Navigate to another page.
6. Return to the login page to check if the saved password autofills.
7. Assert that the autofill is successful.