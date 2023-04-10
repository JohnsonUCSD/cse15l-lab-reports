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
*save your account and password as we will need it soon*
2. Download [git](https://gitforwindows.org/) for windows
- If you are on mac, git should already be installed
3. Use git bash as the default terminal in VS Code by following the instructions below
- [How to use Bash in VScode](https://gitforwindows.org/)
4. Open terminal in VScode
5. In the terminal, use the following command with your course-specific account:
- `$ ssh cs15lsp23--@ieng6.ucsd.edu`
- Remember that the `--` is the letters for your account and that you do not include the `$`
- 
## Trying Some Commands
