# TwitterDatabase
## This is the final project for  courses SQL101-SQL102-SQL103 ##

When talking about social networking sites, we see that Twitter is one of the most popular sites for communication between users, allowing you to communicate with thousands of people from several different regions, as each user registers and a personal profile is created for him through which he sees the user name, account creation date, profile About the user, followers, followers, tweets, and tweet likes. Simulate Twitter to include all users' data (such as email), their profiles which include information about the user (such as username), follow-up details between users, Tweet details (such as the content of the Tweet), and likes on the Tweet (who liked the Tweet).

Note: Not all the attributes are mentioned. The project can be solved in more than one form, i.e. there is no specific form for the correct solution.

Requirements:

    Before applying to SQL, extract the relationships and columns and draw them using an ER diagram, then apply.
    When deriving relationships make sure they are applied between tables (add foreign key).
    Attach ER diagram.
    Create the database.
    Create the required tables with relationships.
    Fill the tables with data and display them.
        Encrypt the user's password.
        When adding any serial number column it should be filled in automatically.
    Create a Procedure named createAccount to which we will pass the user and profile data and it will be added to both tables.
    Create a Procedure named User_Follow we will pass the username itself and the username to follow it will look for the serial number of both users and it will be added to the follow table.
    Show the number of tweets for one user only.

Hints:

    You are not bound by a certain number of entries.
    When you add a new user, the account creation date will be added to the current time automatically.
    The data type of the password is (64)BINARY.
    To encrypt the password, you can use MD5.
    When adding any serial number column you can fill it in automatically without duplication using AUTOINCREMENT.
