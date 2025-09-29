# Git Auto Commit Only

It is a simple plugin that automatically performs only **Git commit** and **push**.  
For security, it is written with minimal code. Without requiring any Git repository access permissions,  
it simply executes the `git add`, `git commit`, and `git push` commands in the current folder.

## Features

1. Automatically executes git commit and push at regular intervals (default: 5 minutes).  
2. Commit & Push button provided to instantly perform the above action.  

![img](https://deok9.com/images/img_auto_commit_1.png)  

## Settings and Notes

- In the Community Plugins settings tab, you can set the interval for auto commits (in minutes). Setting it to 0 disables the function.  
![img](https://deok9.com/images/img_auto_commit_2.png)  
- To work correctly, Git must be initialized and configured in the Vault’s root folder.  
- The default format of the commit message is `auto commit at M-dd-yyyy HH:mm`  
    - example: `auto commit at 12-25-2025 14:57`  

