To built a building, you need materials. To create a website, you need `commands`.
Steps and commands to create your spectacular website:


Step 1: Create a folder

Step 2: Create a file inside the folder and name it `index.html`

Step 3: Add some html lines to the file

Step 4: Create a dummy `index.php` and type the following  in the dummy file
```
<?php
include('index.html');
?>
```
The `index.php` is used to include the `index.html` that you're working at.

Step 5: Type the following command in order to initialize your local `git` repository, and add files into your local
 ```
 git init . 
 git add -A
 git commit -m 'Commit note e.g. don't get sleepy when papa teaches me'
 ```
 
 Step 6: Type the following command to create your desired URL e.g. `myfirstwebsite.herokuapp.com`
 ```
 heroku create myfirstwebsite
 git push heroku master
 ```
 
 Step 7. Enjoy your new website and open it using browser at URL `myfirstwebsite.herokuapp.com`
 Step 8. Keep improving and dreaming!
