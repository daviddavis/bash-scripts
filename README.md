# bash-scripts

**bash-scripts** is a new configuration management utility. Using tried and
tested technologies, anyone familiar with \*-nix systems can get up and running
in seconds. There's no DSL to learn, no boilerplate stuff, no cumbersome
software to install.

## Workflow

Using bash-scripts is easy. Just follow these steps:

1. Write some scripts in bash for configuring your system(s)
2. Deploy your bash scripts to your system (via ftp, sftp, etc)
3. SSH into your system and run the bash scripts

## Comparison to other configuration management tools

* There's no DSL to learn (assuming you know bash already. if not, go back to
  Windows)
* No software to install on your host or client machines
* With the versioning plugin (git) you can easily distribute your code. No
  modules to build, etc
* It's fast
* You're not locked into a vendor or tool. You can easily have puppet or chef
  run your bash scripts.
* Windows is not supported (yes this is an advantage)

## FAQ

### What if I have a bajillion systems?

Just repeat steps 2-3 from the wokflow section as necessary or write a script
to do it for you.

### What does this repo provide?

Not much really. What did you expect?


**If you like bash-scripts, be sure to check out [didnt](https://github.com/daviddavis/didnt) the testing framework**

&copy; 2015 David Davis
