To initiatize git into you current working directory - go to the terminal, move to that directory, and run "git init".
Then go to github, create a new repo, without any readme or licence, then copy the HTTP link.
come back to the terminal and run, git remote add origin "that_http_url",
then run, git add . , this will add all the files and folders in that directory.
then git commit -m "with a message",
then git branch -M main, 
then git push -u origin main.
