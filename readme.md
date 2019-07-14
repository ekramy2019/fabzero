# welcome to fab lab redsea 
-  fab lab 
- lasser cutter 
- vinyle cutter
- 3d printer
- shopbot
## mono fab

 
 :smirk:
 i have to learn 3D on shopbot
 ![my picture]( fablabredsea.png)

 [press to go to the link](https://fablabs.io/)

### convert

convert -rotate 90 fablabredsea.png ekramy.png

convert -resize 200x200 ekramy .png ekramysmall.png 

### remove 

create file      touch hell.png
 remove          rm hell.png
to back file     cd .. 
go into file      ls 

                 rm - rf fablab-redsea/     
nam of file (fabla+tab) 

### when remove file you go to github
 1- fabzero
 2- clone or downlood then press to copy 
 open trmnal  git clone  past (ctrl+shift+v)
 to cheak the file   cd fabzerp/ enter+   ls 

 ### convert PDf in github
 convert file.pdf fil.dwg 

  ###  1.5. <a name='TerminalCommands'></a>Terminal Commands

![terminal](terminal.png)

- ls : used to list all content of the current directory
- clear : used to clear the screen of it's contents
- pwd : used to show the current directory
- cd .. : used to go back one directory
- cd : used to go to the home directory
- cd - : used to go to the last directory
- cd Arduino : used to change current directory to Arduino
- mkdir : used to make directory
- touch : used to make new file
- cat : used to show what is inside the file
- echo : used to show a message on the screen
- echo hello > readme.md : used to send hello to readme.md file
- man : used to show manual
- nano : used to edit text file
- git status : used to know the status of the md file i want to push
- convert : used to manipulate images, resize and rotate and etc.
- rm : used to delete files and folders

###  1.1. <a name='Sofwares'></a>Sofwares

- Free cad
- openscad
- kicad
- inkscape
- openscad
- freecad
- kicad
- gimp
- wine
- vcarve
    sudo apt upgrade
    sudo apt install inkscape
    sudo updat 


### to add file  on github 

- git add
- git commit - m "سبب الاضافة " 
- git push


###  1.7. <a name='Stepsofdealingwithgithub'></a>Steps of dealing with github

1. Sign up github
2. Confirm email
3. login with the registered email
4. Create new respotory (prefet names fabzero for now)
5. There are steps are shown on the new respotory page you should follow as you inside your local folder that contains your readme.md file like
    - git init
      - If the first command faced a problem caused by absent of git, you should follow the instructions appear to fix it
   - git add readme.md
   - git commit -m "first commit"
     - The message between the two symbols "" should be related to the editing
   - git remote add origin https://github.com/fablabgharbiya/fab.git
     - fablabgharbiya: depending on your user name and respotory name
   - git push -u origin master
     - used to push the file to the respotory
6. If you want to edit the readme.md
   - Edit your file
   - Open your terminal
   - Change your directory to the readme.md file
   - Write the following commands
     - git add .
        - used to add all modified files only
    - git commit -m "modified i have made"
    - git push 
7. If you want to delete files and recover it again, in case some thing happend and you want to back to earlier point
8. Deleting data is useful to recover when it lose

###  1.8. <a name='Convertfromhttptossh'></a>Convert from  http to ssh

1. ssh-keygen -t rsa -b 4096 -C "your_email@example.com" : This creates a new ssh key, using the provided email as a label.
2. Enter a file in which to save the key (/home/you/.ssh/id_rsa): [Press enter]
3. Enter passphrase (empty for no passphrase): [Type a passphrase]
4. Enter same passphrase again: [Type passphrase again]
5. eval "$(ssh-agent -s)" : Start the ssh-agent in the background, Agent pid 59566
6. ssh-add ~/.ssh/id_rsa : Add your SSH private key to the ssh-agent
7. Then add ssh to my github
8. sudo apt-get install xclip : to copy the ssh key to my github
9. xclip -sel clip < ~/.ssh/id_rsa.pub
10. then head to github website and choose setting from the ubber left
11. ssh and gpg keys
12. new ssh key
13. paste the key
14. add ssh key
15. confirm password
16. get the ssh from get clone button
16. then head to termianl and check the remote site by using git remote -v
17. begin to replace http by ssh we get from the get clone button using command : git remote set-url origin "paste the link here"
18. done >>> weeeeee
