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
      * mv filename newfilename **(renaming)**
      * mv filename directoryPath/newfilename **(moving a file)**
7. **rm**: remove a file
      * -r (recursive, can)
      * -f (force remove without pesky recursive questions)
      * -rf can be used to nuke directories in place of **rmdir**
8. **PS1=">"**: changes the prompt to a karrat 
9. **~**: Points to whatever the HOME variable is 
10. **alias command** lets you create a unique command
      * alias ls="ls -al --color"
11. Command **--help**: gives you info about a command 
12. **man command**: brings up the full manual for a specific cammand
13. **wc file name**: gives you the word count in a file
      * **-l**: gives you the number of lines
14. **wget http:**: pulls files from the internet
      * good for pulling data files from the internet
15. **cat filename**: print to screen
      * cat filename1 **filename2**: concatinate files & print
      * cat filename1 filename2 **>** filename3 (adds bothfiles to a new file)
         * **If the file already exists, you will overwrite it!!**
            * Use **>>** to append to the **END** of the file
16. **control + ___** Shortcuts 
      * **a**: moves cursor to to the beginning of the line
      * **e**: cursor to end of line
      * **k**: deletes everything from the cursor through the end of the line
      
      
