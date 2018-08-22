
These are some examples of how to use SQL commands. See below for instructions on how to set up and use this application

# INSTALLATION

First, download this repository. Then follow the bullet points below.

1. Make sure you have MySQL Community Edition and MySQL Workbench downloaded and installed (Follow the instructions [here](https://dev.mysql.com/downloads/mysql/) and [here](https://dev.mysql.com/downloads/workbench/). Default settings for everything should be fine).

2. Open Git Bash. If you're using Windows, [download it](http://gitforwindows.org/) and follow the instructions (again, default settings should be okay). Mac and Linux users can use the built-in terminal application.

3. `cd` to the directory this file lives in

4. Create a file called 'config.js' and fill it with the following, replacing the username and password fields with the credentials you used for setting up MySQL:

```
module.exports = {
    username: 'your_mysql_username',
    password: 'your_mysql_password'
};
```

5. run `npm install`


# USAGE

The examples are all in the 'exercises.sql' file. You can verify they work by running `npm test`. If you feel like punishing yourself, you can modify the tests or create new ones by looking in the 'test/test.specs.js' file.

The database being used is a sample called sakila. It should already be included in this project. You can use the Workbench to explore around the database, and see what different SQL instructions actually do.
# mysql-exercises
