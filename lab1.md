# **How to Remote Access CSE 15L**

## Installing VSCode
1. Go onto the [VSCode](https://code.visualstudio.com/) website -  [https://code.visualstudio.com/](https://code.visualstudio.com/)
2. Click on the carat to drop down and download the [VSCode](https://code.visualstudio.com/) installer for your OS
![Image](https://github.com/JohnsonUCSD/cse15l-lab-reports/blob/main/VSCodeSS.png)
3. Run the installer and follow the intructions on it
![Image](https://github.com/JohnsonUCSD/cse15l-lab-reports/blob/b589f2257566e5b7a04c32616f0dc1c15ee8da3c/Code_zp2Z127h70.png)
- After you are done you should see a screen that looks similar to this


## Remotely Connecting
1. Look up your course-specific account for CSE15L using this link: 
  - [https://sdacs.ucsd.edu/~icc/index.php](https://sdacs.ucsd.edu/~icc/index.php)
    - If it is your first time accessing this account, you need to reset your password to set a password
    - If you are having trouble, here are the [instructions to reset your CSE15L password](https://drive.google.com/file/d/17IDZn8Qq7Q0RkYMxdiIR0o6HJ3B5YqSW/view)
  - The course specific account should look something like cs15lsp23--@ieng6.ucsd.edu with the -- being some letters for your course-specific account
> *save your account and password as we will need it soon*
2. Download [git](https://gitforwindows.org/) for windows and follow the instructions
  - If you are on mac, [git](https://gitforwindows.org/) should already be installed
3. Use git bash as the default terminal in VS Code by following the instructions below
  - [How to use Bash in VScode](https://stackoverflow.com/questions/42606837/how-do-i-use-bash-on-windows-from-the-visual-studio-code-integrated-terminal/50527994#50527994)
4. Open terminal in VScode
5. In the terminal, use the following command with your course-specific account:
- `$ ssh cs15lsp23--@ieng6.ucsd.edu`
- Remember that the `--` is the letters for your account and that you do not include the `$`
  - If it is your first time you will probbaly get a message similar to this, so type `yes` and then enter
![Image](https://github.com/JohnsonUCSD/cse15l-lab-reports/blob/61dab5603f07104b7c16b3b932a8f64d8438187a/nexon_client_h1RyPmstir.png)
- Once you've done that it will now ask for your password, so type the password you created for your course-specific account
> The password might not look like it is being typed, but it is, so keeep trying
> It could also be the case that you just need to wait for your course-specific account password to update
6. Once logged in, you will see a message similar to this:

![Image](https://github.com/JohnsonUCSD/cse15l-lab-reports/blob/63116364987bef065e8b3f147c293e64b1d02750/nexon_client_yUyu8J5pYh.png)

Congratulations! Your terminal is now connected to a computer in the CSE basement
## Trying Some Commands
Now that you are connected, try running some code

![Image](https://github.com/JohnsonUCSD/cse15l-lab-reports/blob/33ceefeaca28485002519df29a0763d4a48f533e/nexon_client_nCLKxRAgzf.png)

More you can try out:
- `ls /home/linux/ieng6/cs15lsp23/cs15lsp23--` with `--` being one of your group member's username
- `cp /home/linux/ieng6/cs15lsp23/public/hello.txt ~/`
- `cat /home/linux/ieng6/cs15lsp23/public/hello.txt`
- 
As an example, here are some commands that I used together:

![Image](https://github.com/JohnsonUCSD/cse15l-lab-reports/blob/416bb54a69d5ea429701148dddf100a0e83b3215/chrome_u4H6kAGde4.png)

To log out of the remote server in your terminal, you can do
- Ctrl + D
- Run the commmand `exit`
