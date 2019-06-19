## BOOKMARK MANAGER WEEK 4

## BRIEF

Build a web app that stores web bookmarks in a database.

## WEBSITE REQUIREMENTS

- Show a list of bookmarks
- Add new bookmarks
- Delete bookmarks
- Update bookmarks
- Comment on bookmarks
- Tag bookmarks into categories
- Filter bookmarks by tag
- Users are restricted to manage only their own bookmarks

### USER STORIES

#### USER STORY 1: LIST BOOKMARKS

```
As a user
So that I can easily access my favourite websites
I would like to see a list of my bookmarks
```
#### DOMAIN MODEL DIAGRAM https://raw.githubusercontent.com/makersacademy/course/master/bookmark_manager/images/bookmark_manager_1.png?token=ACBIYNQILECHGGTY4NZVO6S5CDLUQ

### DATABASE

#### To set up the database

- Connect to `psql`
- Create the database using the psql command `CREATE DATABASE bookmark_manager;`
- Connect to the database using the pqsl command `\c bookmark_manager;`
- Run the SQL scripts in the `db/migrations` folder in the given order.

### To run the Bookmark Manager app:

`rackup -p 3000`

To view bookmarks, navigate to `localhost:3000/bookmarks`
To view bookmarks, navigate to `localhost:3000/bookmarks`.

### To set up test database
```
$> psql
admin=# CREATE DATABASE "bookmark_manager_test";
admin=# CREATE TABLE bookmarks(id SERIAL PRIMARY KEY, url VARCHAR(60));
```

### To run tests:
