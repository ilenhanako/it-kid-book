#Chapter 9: Heroku the hero

Heroku is similar to Github, however it is more advanced. In chapter 7, you have created your own Heroku account.
In this chapter you will learn how to use Heroku.

_This is so exciting! Let's get started!_
 
 
##Practice:      

- [ ] Install Heroku Toolbelt

After you have install heroku toolbelt, you could run heroku command in terminal.

- [ ] Try with various heroku command. 
```

heroku login
heroku create (type your prefered website name after you have type in heroku create)

```
- [ ] Then create a website project. 

You will have your first website now called http://ilen.heroku.com (or whatever name you want)

* You have to create your website locally ~ using TextMate and test it using Google Chrome
* Then push the update to heroku by running following command
 
``` 
 git add -A
 git status (is optional -- only for me to see the changes)
 git commit -m 'any message'
 git push heroku (this is the real command to push out the changes to heroku)

```