Tristan Cooper - A17085814
# Week 1 Lab Report: Remote Access Tutorial
*Welcome CSE 15L Students!*

### STEP 1: Installing VScode
__Background Info:__ Visual Studio Code is a text editor made by Microsoft, and is likely the most popular text editor used today.
1. If VScode is *not already installed* on your machine, visit their [website](https://code.visualstudio.com/) to download and install it. 
>                         HINT: Remember to select the correct version for your operating system!
2. *Now that VScode is installed* on your machine, go ahead and open it up. 
- With the exception of some minor differences like the theme, your window should look something like this:

![First VScode screenshot](/blank-vscode-screenshot.jpg "First VScode screenshot")
    

### STEP 2: Remotely Connecting
__Now it's time to connect to a remote server!__
1. *First*, you're going to need to be running `git`

To check if you already have `git` installed on your machine, run the following command in the terminal: 
                                                    `git --version`
                                                    
|Checking if `git` is installed                |
|:--------------------------------------------:|
| If the terminal prints something like this... |
|![image](https://user-images.githubusercontent.com/78113615/211945415-283d76c4-915e-44fb-871c-35e85423100a.png)|
|__... then you're all set!__                   |

If you get an error message, probably saying that `git` wasn't found, download [__Git for Windows__](https://gitforwindows.org/)

2. Next, you're going to need to set `git bash` as your default terminal.
        
        Remember, this is all still in VScode. So, navigate to the "Terminal" tab in your window, and select "New Terminal" from the dropdown.
        
***For further instructions, please reference [this](https://stackoverflow.com/a/50527994) stackoverflow page.***

3. Have your specific CSE 15L account handy, because it's time to use `ssh` to connect to the server!

You can search for your account [here](https://sdacs.ucsd.edu/~icc/index.php)

> Use this command in the terminal: `ssh cs15lwi23XXX@ieng6.ucsd.edu` where XXX is your unique username suffix.

5. Next, __enter your password.__ 

NOTE: the terminal typically doesn't display any characters as you type your password. 
*It can be a little jarring at first, but not to worry, it's completely normal!*

- ***Once you've entered your password, the terminal should display something similar to this image:***


![image](https://user-images.githubusercontent.com/78113615/211948364-9298cd2c-7b1f-4b02-8ee2-7d3fd0c0cb82.png)


> Congrats! You're now connected to the remote server! There's just one more step...

### STEP 3: Trying Some Commands

Finally, feel free to try entering some of these commands at the command line:

![image](https://user-images.githubusercontent.com/78113615/211949180-50ebd59d-79e9-4ab3-995f-70febbf887dd.png)






