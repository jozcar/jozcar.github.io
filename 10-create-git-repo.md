**Creating a Repo on Github.com**

Go to github.com and create a repo for your library. once you have created a repo you need to create a local reposatory on your local computer.  

There are two way to do this.

1.  You already have you code on you local computer.

        Run the following commands.

```
    git remote add origin https://github.com/your_user_name/repo_name.git
    git push -u origin master
```

2. Start from Scratch

Use the following commands.

```
echo "# Read me message" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/your_user_name/repo_name.git
git push -u origin master
```

Note, that when you create a repo the above instruction are given to you, so you can copy and paste then into your terminal. provided that your terminal is already pointing to your working directory.









