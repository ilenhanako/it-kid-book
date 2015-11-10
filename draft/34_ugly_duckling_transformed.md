# Ugly Duckling Transformed

Ugly duckling is a special duck, magnificent and powerful. Unfortunately, ugly.
But never mind.

Today we'll transform the ugly duckling of your computer i.e. Terminal to be a _"beautiful swan"_.

## Practice

- [ ] In your terminal, move to home directory. 
```
Command **cd**
```
- [ ] Create a file in home directory and name it as **.bash_profile** . The file may already __exist__ , if so use that file and open it.


- [ ] Put below as the content of the file. If the file exists, just add it in the bottom of the file
```
emojis=(🐶 🐺 🐱 🐭 🐹 🐰 🐸 🐯 🐨 🐻 🐷 🐮 🐵 🐼 🐧 🐍 🐢 🐙 🐠 🐳 🐬 🐥)
emoji='`echo ${emojis[$RANDOM % 22]}`'
export PS1="$emoji \W $ "
```
- [ ] Close your terminal, and try to open it. Guess what's happenning?
