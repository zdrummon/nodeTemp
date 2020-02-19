# nodeTemp
node experiment space



# Setup:
1. Search Windows for "turn windows features" and select the first option
2. Enable linux subsystem for windows (WSL)
3. Install Ubuntu from the Windows store
4. Install VSCode
5. Open VSC and press F1: select "Remote-WSL: new window" and close old VSC window
6. Open VSC terminal and set to BASH
7. Type the following commands to install relevant tools:
<br>A. sudo apt-get install nodejs
<br>B. sudo apt-get install npm
<br>C. sudo apt-get install npx
<br>D. sudo apt-get install git
8. Type the following commands to configure and clone the github repo
<br>A. mkdir dev
<br>B. cd dev
<br>C. git config --global user.name [github userID]
<br>D. git clone https://github.com/zdrummon/nodeTemp.git
<br>E. cd nodeTemp
<br>F. npm install
9. Press "Ctrl + Shift + E" and click on "open folder" and then navigate to nodetemp and press OK
10. Open and edit this README.md file by adding a unique phrase to the bottom
12. Press "Ctrl + Shift + G" and click the check mark at the top
12. Press "Save All & Commit" and add the message "first commit"
14. Click on the hamburger icon at the top right and select "Publish Branch"
15. Bonus: make a shortcut   and go to its properties and replace the target path with "C:\Windows\System32\bash.exe -c "code"" to create a shortcut for VSC WSL
16. Bonus: search for and install these extensions-
<br>A. ESLint
<br>B. GitLens
<br>C. REST Client

# Running express:
17. Type node bin/www in terminal
18. Type http://localhost:3000/ in your browser
19. Tada! You have a working system. Press ctrl + C in terminal to end the server