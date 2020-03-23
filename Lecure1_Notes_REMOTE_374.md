# Lecture 1 

#### R Studio Cloud

1. PS1=">" (Changes the Terminal Prompt)
     
#### Creating a Repository  

1. Create New
2. Title & Brief Description
3. ALWAYS initialize with a README
    
#### Cloning a Repository & Editing in R Studio Cloud
1. Copy Repository http link
2. open R Studio cloud terminal 
3. go to go to sandbox directory
4. Enter: ***git clone http:...***
5. This lets you access the repository 
6. You can use ***touch*** command create new empty file
7. Enter: ***git add filename*** (prepares files to be committed) 
8. Enter: ***git commit filename*** (commits changes to local repository)  
     * ***-a*** lets you skip the git add step and prepares all changed files
9. Enter: ***git push origin master*** (commits changes to remote repository)
10. Enter: ***git rm filename*** (opposite of git add... same steps going fwd)

#### Markdown Language 
1. \# Heading (More hashtags -> smaller heading text)
2. \*Bullet Point
3. \(tab)* Indented Bullet
4. Separate paragraphs: empty line
5. Line Break: end line with 2 spaces and start new line
6. \**Bold text**
7. \*italic text*
8. \***bold & italic***
9. \> Block Quote 
10. \>> Embedded Block Quote

#### R Notebook
1. **Uses Markdown and embedded R code to make analytical presentation slides**

#### Unix 
1. Format: [Command] [Optons] [Argument]
2. echo: print
3. ls: list conents on working directory
4. pwd: print working directory
5. cd: change directory 
6. clear: clear terminal 
