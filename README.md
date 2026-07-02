#Git Branching and Merge Conflict Reflection

##During this assignment, I learned how to use Git to manage different versions of a project by creating and working with branches. 
I started by initializing a new Git repository and creating an index.html file with basic HTML. After making my initial commit, 
I created a new branch called feature/header using the git checkout -b command. On this branch, I added a header section to the webpage, 
staged the changes, and committed them. I then switched back to the main branch and created another branch named feature/footer, 
where I added a footer section and committed those changes as well.
To simulate a merge conflict, I switched back to the feature/header branch and added another footer section. 
Because both feature branches modified the same part of the index.html file, Git was unable to automatically determine which changes 
should be kept when I merged the branches into the main branch. When I attempted the second merge, Git displayed conflict markers in the file. 
I opened the file in Visual Studio Code, reviewed the conflicting sections, removed the conflict markers, combined the changes that 
I wanted to keep, and saved the file. After verifying that the file was correct, I staged the resolved file and created a new commit to complete 
the merge.
The pull request process is an important part of collaborative software development because it provides an opportunity to review changes before 
they are merged into the main branch. Pull requests allow team members to examine code, suggest improvements, identify bugs, and ensure that coding standards are followed. 
They also serve as documentation by explaining the purpose of each set of changes and creating a history of discussions and approvals. 
Although I completed this assignment individually, I now understand how pull requests help teams maintain code quality, reduce errors, 
and improve collaboration by encouraging communication and careful review before code becomes part of the main project.
