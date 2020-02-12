# Assignment 
1. Assuming that you aren't sure whether you're currently inside of a Git repository, write the command (or commands) that will give you this information.
    - ``` ls -a ``` : (By this we can check whether  **.git** file is present or not.)
    - ``` git status ```: (If repository is not intialized it would give the error.)
2. Assuming that you are currently within a Git repository, write the command (or commands) that will cause the file 'hello-world.txt' to be committed.
    - Before committing we need to check wether the file is staged or not , if not,to stage the following command is used - ``` git add filename ```
    - Commit can be done in two ways :
        - ``` git commit```: after execution it will open a vim window for us to write the commit message.
        - ``` git commit -m "message" ```: Here we can apply message  directly to the command line .
