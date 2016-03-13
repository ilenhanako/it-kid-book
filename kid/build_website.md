 To built a building, you need materials. To create a website, you need commands.
 Steps and commands to create your spectacular website:

Step 1: Create a folder

Step 2: Create a file inside the folder and name it (index.html)

Step 3: Add some html lines to the file

Step 4: Create a dummy 'php file' and type the following commands in the dummy file
```
<?php
include('index.html');
?>
```
The above command was used to include the 'html file' to the 'php file'.

Step 5: Type the following command in order to create your website's URL.
 ```
 git init . 
 heroku create (E.G.  abcd.herokuapp.com)
 git push heroku master
 ```
 For any changes
 ```
 git add -A
 git commit -m 'Commit note e.g. don't get sleepy when papa teaches me'
 ```
