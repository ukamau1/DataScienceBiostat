# Lecture 2 Notes   

#### More Unix     
1. **echo**: unix print command 
2. **whoami**: Let's you know who you are 
3. **ls**: list contents of working directory 
    * -al: show hidden files too
    * .Rhistory: hidden files that saves commands used
4. **chmod**: change permissions for a file (make it executable)
    * chmod u+x filename
5. **pwd**: print working directory 
      * **.**: current directory
      * **/**: root directory 
      * **..**: one directry back 
6. **mv**: used to change file names 
      * mv filename newfile name 
      * mv filename directoryPath/newfilename (moving a file)
7. **rm**: remove a file
      * -r (remove a directory)
      * -f (force remove without pesky recursive questions)
7. **PS1=">"**: changes the prompt to a karrat 
8. **~**: Points to whatever the HOME variable is 
9. **alias command** lets you create a unique command
      * alias ls="ls -al --color"
