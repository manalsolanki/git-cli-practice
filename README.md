# Assignment 
1. Assuming that you aren't sure whether you're currently inside of a Git repository, write the command (or commands) that will give you this information.
    - ``` ls -a ``` : (By this we can check whether  **.git** file is present or not.)
    - ``` git status ```: (If repository is not intialized it would give the error.)
2. Assuming that you are currently within a Git repository, write the command (or commands) that will cause the file 'hello-world.txt' to be committed.
    - Before committing we need to check wether the file is staged or not , if not,to stage the following command is used - ``` git add hello-world.txt ```
    - Commit can be done in two ways :
        - ``` git commit```: after execution it will open a vim window for us to write the commit message.
        - ``` git commit -m "message" ```: Here we can apply message  directly to the command line .
3. Assuming that you are currently within a Git repository, write the command (or commands) that will display any uncommitted changes made to the file named 'README.md'.
    - ``` git diff README.md ```:(Will show the contacts which are not commited)
4. Assuming that you are currently within a Git repository, write the command (or commands) that will display the changes from the commit with the ID of abc123.
    - ``` git show abc123 ``` :(Will compare with the previous commit and display the changes.)
5. Assuming that you are currently within a Git repository, write the command (or commands) that will display the ID and commit message for the 3 most recent commits.
    - ``` git log --oneline -3``` :(Here log tells the histroy of commit ,oneline tells that show only commit id and message and 3 represent the most 3 recent commits.)
6. Assuming that you are currently within a Git repository, write the command (or commands) that will check to see if the remote repository contains any new commits.
    -  This can be achieved by two commands.
        -  ``` git fetch ``` To check whether local is aware of all the commits made to remote repositary.
        - ``` git status``` So local and remote are not sync , we can get to know that which is running behind.
        - In our problem it will show  remote is ahead of n commits. So now we will know that this are the new commit and we can pull them.


