To built a building :bank:, you need materials. To create a website, you need `commands`
Steps and commands to create your spectacular website:

- [x] Create a __folder__ :file_folder:(Command in terminal: mkdir "your website name')

- [x] Create a __file__ :page_with_curl: inside the folder and name it `index.html`

- [x] Add some html lines :straight_ruler: to the file

- [x] Create a dummy `index.php` and type the following text in the dummy file :page_with_curl: . The `index.php` :arrow_upper_left: is used to include the `index.html` that you're working at.
`
<?php
include('index.html');
?>
`
- [x] Type the following command :memo: in order to initialize your local `git` repository, and add files into your local

```
 git init . 
 git add -A
 git commit -m 'Commit note e.g. don't get sleepy when papa teaches me'
```
 
 - [x] Type the following command to create your desired URL e.g. `myfirstwebsite.herokuapp.com`
 ```
 heroku create myfirstwebsite
 git push heroku master
 ```
 
- [x] Enjoy your new website and open it using browser at URL `myfirstwebsite.herokuapp.com`:bowtie:
 
- [x] Keep improving and dreaming!:star2::+1::sparkles::mortar_board:
