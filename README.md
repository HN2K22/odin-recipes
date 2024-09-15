# odin-recipes

Learned a Lot about git and how it is a different approach to commit changes in github.

we use git clone git@github:USERNAME/REPOS_NAME.git to clone a repository

To add the file in unstaged phase : git add fileName.

to commit it on the history : git commit -m (if the changes are fairly short )
                              git commit (if the changes needs to have a descriptive explanation with structure)

while commiting the changes that are fairly big there is  a structure to follow

to revert a commit in github use "git revert HEAD" as it will add a revert and original text in commit which u can delete or use it as ref
along side can add body to it. It is safe to use in Public Branch

another way to revert a commit is to use "git reset HEAD~1" to delete a commit which will revert it to unstaged phase for the last commit
and to push this revert commit use "git push -f origin push" where -f is used as a forced flag maker sure this is ur private repos as,
it's not a good practice to delete commit in public branch.

Subject/Title for the Changes  (Needs to be less than 50 characters) also capitalize the first word and write it in more programmed terms
example - "Clean your room"

<-- blank space for formating it in regards to body>

Body mostly mult lined and no limit in terms of descriptive explanation

