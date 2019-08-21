\\ git 

\\ \\ one time setup

`git config --global user.name "Cayden Lloyd"`
`git config --global user.email "edward2020lloyd@gmail.com"`


\\ \\ project setup

`git init`

\\ \\ 3 step repeating commit process
 1. Make changes to cod 
 2. stage related change 
	*git add
 3. commit changes with a message command
 	* git commit -m ""

 * status -> tell me what files have beem staged or committed
 * add -> add a file to the stage
 * rm --cached -> remove file from stage
 * git commit -m "Present tense description of what changed"
 * git log -> enter to move down, q to quit

\\ \\ Problems
* commit without -m -> use esc :wq to quit Vim
* wrong messsage -> git commit --amend -m "New Message"