**Publishing you Library to NPM.**

You need to have an account on NPM in order for you to be able to publish your library, there are two ways to do this.

1. through your terminal 

   2. though npm website.

    this is the simplest way of doing it, create the account this way.  once you have you account created, you are ready to start publishing your library.



**Open your Terminal**

Navigate to the directory where you have you code.  the first step to login into npm via the terminal.  

```
> npm login 
```

  hit enter, and just enter what is ask.  once you are logged in

```
> npm publish
```

 this command will publish your library to npm,  if you get an error by running the command above, chances are that your package name is already taken,   the error won't tell you this, but to find this out, just search the name of your package on npm , if you found it, then you update the  name on you package.json file, and type _npm publish_ again.

if all goes well, you will get the name of your library on the command prompt.  you can go to the npm website and under your account, and you will see your library there.

**Testing Your Package**

1. create a directory on your computer
2. npm i name-of-your-library
3. create a test page.



