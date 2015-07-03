# python


# ok so these are the directions to use the command line so as to make a new file in GIT repository:

#--------------------------------------------------------------------------------------------------------------------

1)  echo "# python" >> README.md    (this is the file in which this information is saved)
2)  git init
** should return ** 
" Reinitialized existing Git repository in /Users/simeonmeerson/.git/ "

3)  git add README.md
4)  git commit -m "first commit"    (Committing the added file to the repository (just like in SVN))
** should return **
"

[master (root-commit) a944f0f] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
 
"

5) 

Copied and Pasted from Command line (Terminal):


Simeons-MacBook-Pro:~ simeonmeerson$  git remote add origin https://github.com/smeerson/python.git
Simeons-MacBook-Pro:~ simeonmeerson$   git push -u origin master

** PROMPTING NOW TO LOG INTO REPOSITORY **
Username for 'https://github.com': smeerson
Password for 'https://smeerson@github.com': 
** ENTERED REPOSITORY **

** SHOULD RETURN : **
Counting objects: 3, done.
Writing objects: 100% (3/3), 217 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/smeerson/python.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.


** BACK TO COMMAND LINE ON LOCAL DIRECTORY **
Simeons-MacBook-Pro:~ simeonmeerson$ 





#--------------------------------------------------------------------------------------------------------------------
