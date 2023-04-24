# Post-It Note

**Tier:** 2-Intermediate

It’s human to have many thoughts and ideas in a day, but it’s also human to forget.
One way to work around forgetting things is to jot them down before they disappear into thin air.
While some of forgotten thoughts and ideas may be trivial, some can be quite powerful.
This is where a Post-It note comes in: A Post-It note is a small paper with low-tack adhesive at the back, making it attachable to surfaces such as documents, walls.
Post-It notes make it easier to jot things down.
The Post-It note project idea is something similar.
It allows users to jot things down, making them accessible anywhere, since it’s a web application.
With the Post-It note, people can now jot things down anywhere, without the fear of forgetting things or misplacing the notes—which is a possibility with physical notes.

## Technical Details

The main objective of this project is to allow users to jot down thoughts.
This means that each user will have their own notes, so the application will need to have an account creation feature.
This ensures that the notes of each user remain private to them.
django comes with a user authentication system, so it may be a good choice.
You can use other frameworks like bottle or flask, but you’ll have to implement the user authentication system on your own.
Since users may need to separate their notes under different sections, implementing a feature to allow users to categorize their notes will make the application more useful.
As an example, you may need to have notes on algorithms and data structures, so you’ll need to be able to separate the notes in those categories.
You’ll need to store the information and notes of each user, so a database becomes an essential part of this project.
The MySQLdb module can be used if you want to use a MySQL database or the psycopg2 module for a PostgreSQL database.
There are other modules you can use, but it all depends on the database you choose to use.

## Extra Challenge

Since it’s human for users to forget their ideas, it’s also human for them to forget that they even made a note somewhere.
You can add a feature to remind users of their notes.
This feature will allow users to set a time for the reminder, so the application will send the reminder to the users when it’s time, by email.

## Example projects

Here is Pinup website for giving you some ideas:

-   [PinUp](https://pinup.com/O5NtEl8xl)
