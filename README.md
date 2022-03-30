# header

Some Text

to put a repo from a local machine created to the git profile, we use the cmmd, git init

Since I created the repo locally, the git push, cmd doesn't know the "origin", hence we need to create one. The easiest way is by creating one repor in the GitHub.com page..

Then, we link the repo by using the command, git remote add origin git@github.com:Khesehang-Limbu/Repo-2.git //this is the SSH // To add a reference to the Git repo that we created.
//Here, remote is just something that indicates that something is there but not in the local machine.

And to check whether the connection is there or not, we use the command, git remote -v

And if I don't want to type, git push origin master, everytime to get the repo online, I need to create a upstream, which can be done so, by using the command, git push -u origin master, this will allow me to use the "push" instruction, with just, git push.

# Branching 

to check how many branch you have, you use the command, git branch
and to create a new branch, we use the command, git checkout -b descriptive_name
to switch between banches, we need to use the, git checkout name_of_branch

## Local Development

1. Branching...
