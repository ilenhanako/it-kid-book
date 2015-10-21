# Ugly Duckling Transformed

Ugly duckling is a special duck, magnificent and powerful. Unfortunately, ugly.
But never mind.

Today we'll transform the ugly duckling of your computer i.e. Terminal to be a _"beautiful swan"_.

## Task

- [ ] In your terminal, move to home directory. 
```
Command **cd**
```
- [ ] Create a file in home directory and name it as **.bash_profile** . Don't ask me now why it is named as **.bash_profile**

- [ ] Put below as the content of the file

export PATH=${PATH}:/Applications/adt-bundle-mac-x86_64-20140702/sdk/platform-tools:/Applications/adt-bundle-mac-x86_64-20140702/sdk/tools
emojis=(🐶 🐺 🐱 🐭 🐹 🐰 🐸 🐯 🐨 🐻 🐷 🐮 🐵 🐼 🐧 🐍 🐢 🐙 🐠 🐳 🐬 🐥)
emoji='`echo ${emojis[$RANDOM % 22]}`'
export PS1="$emoji \W $ "

- [ ] Close your terminal, and try to open it. Guess what's happenning?
