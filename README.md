# initialize command for github repository

# create a new repository on the command line

echo "# github_repo_commands" >> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin git@github.com:stackpl/github_repo_commands.git

git push -u origin master

# or push an existing repository from the command line

git remote add origin git@github.com:stackpl/github_repo_commands.git

git push -u origin master
