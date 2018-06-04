# Final Deliverables

## Team Members & Contributions
**Kellie Higa**

- [contributions]

**Eunice Kim**

- Helped create prototype 2
- HTML/CSS/JS front-end coding such as the habits page, accounts page, modals, buttons, and the UI of the data visualization.
- Coded some Firebase requests such as logging and displaying the points on the home page, updating the avatar's appearance in the closet by updating the database, and updating the home page avatar.

**Shelly (Ji) Bae**

- Mockup of lo-fi/hi-fi prototypes and wireframes
- Set up some Ajax requests
- HTML/CSS/JS front-end coding
- SQLite/Firebase requests

## Source Code Files & Functionality
1. **add_accessories.js:**
SQL Queries to initialize the accessories database for the store by inserting accessory item data into database

2. **create_database.js:**
Initializes all required SQL Databases (e.g. for user's & children's accounts, accessories, habits, etc.)

3. **server.js:**
Held POST/GET requests when using Ajax. Initializes Express and SQLite3 database.

4. **accounts.html:**
Displays a list of user's children's accounts to choose from. User can add accounts for children and logout.

5. **accounts.css:**
Stylesheet for accounts.html

6. **accounts.js:**
Displays user's children's accounts and saves to localStorage the child's and user's ID when selected. Allows user to add an account for child. Allows logout.

7. **app.js:**
Initializes Firebase.

8. **closet.html:**
Displays child's pet and child's owned/purchased accessories. Child can select different accessories to dress up his/her pet.

9. **closet_style.css:**
Stylesheet for closet.html

10. **closet.js:**
Displays owned accessories and displays preview of pet wearing selected accessory when clicked.

11. **habit_stats.html:**
Displays statistical information for selected habit and child's progress. Allows user to edit habit.

12. **habit_stats.css:**
Stylesheet for habit_stats.html

13. **habit_stats.js:**
Grabs selected habit's data from database and displays relevant information such as past logs, progress, setbacks, etc. Allows user to make changes to habit data.

14. **habits.html:**
Displays list of habits (description, due date) assigned to child. Allows user to add new habit.

15. **habits.css:**
Stylesheet for habits.html

16. **habits.js:**
Fetches child's habit data from database and displays relevant information. Updates habit database if user creates new habit.

17. **home.html:**
Homepage, displays child's pet and points. Upon first visit of the day, user/child is prompted to log daily habits.

18. **home_style.css:**
Stylesheet for home.html

19. **home.js:**
Fetches child's account data from database to display child's pet, number of points, and habits to log. Logged habits are updated.

20. **login.html:**
Allows user to login to his/her account using email, Google account, or phone number.

21. **login_style.css:**
Stylesheet for login.html

22. **login.js:**
Access Firebase to allow user login and account authentication.

23. **pin.html:**
Allows user to set up pin code to lock certain features from child access.

24. **signup.js:**
Access Firebase to allow user to signup using email, Google account, or phone number.

25. **start_firebase.js:**
Initialize Firebase database for current user.

26. **store.html:**
Displays accessories available to purchase for child's pet using his/her accumulated points.

27. **store_style.css:**
Stylesheet for store.html

28. **store.js:**
Grabs child's data from database for number of points available to spend, accessories not purchased yet to display in the store, and update database when selected item is purchased.
