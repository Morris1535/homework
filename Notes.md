cd - allows you to move to another folder

`Sam Morris@DESKTOP-EMUTIU5 MINGW64 ~`
`$ cd desktop`

`Sam Morris@DESKTOP-EMUTIU5 MINGW64 ~/desktop`
`$ cd "sparta global"`

`Sam Morris@DESKTOP-EMUTIU5 MINGW64 ~/desktop/sparta global`
`$ cd github`

git clone - allows you to create a local repositories from URL

`Sam Morris@DESKTOP-EMUTIU5 MINGW64 ~/desktop/sparta global/github`
`$ git clone https://github.com/Morris1535/homework`

cd - moving into the local repository

`Sam Morris@DESKTOP-EMUTIU5 MINGW64 ~/desktop/sparta global/github`
`$ cd homework`

git add - adding file to include when you push

`Sam Morris@DESKTOP-EMUTIU5 MINGW64 ~/desktop/sparta global/github/homework (main)`
`$ git add README.md`

git commit - records the file permanently in the version history

`Sam Morris@DESKTOP-EMUTIU5 MINGW64 ~/desktop/sparta global/github/homework (main)`
`$ git commit --m "Update"`

git push - sends the committed changes to the remote repository

`Sam Morris@DESKTOP-EMUTIU5 MINGW64 ~/desktop/sparta global/github/homework (main)`
`$ git push`

git check -b - creates a new branch and switches you to it

`Sam Morris@DESKTOP-EMUTIU5 MINGW64 ~/desktop/sparta global/github/homework (main)`
`$ git checkout -b Sam`

git push -- set-upstream origin Sam - pushes new branch to the remote repository 

`Sam Morris@DESKTOP-EMUTIU5 MINGW64 ~/desktop/sparta global/github/homework (Sam)`
`$  git push --set-upstream origin Sam`



`Sam Morris@DESKTOP-EMUTIU5 MINGW64 ~/desktop/sparta global/github/homework (Sam)`
`$ git add README.md`



`Sam Morris@DESKTOP-EMUTIU5 MINGW64 ~/desktop/sparta global/github/homework (Sam)`
`$ git commit --m "New Update"`



`Sam Morris@DESKTOP-EMUTIU5 MINGW64 ~/desktop/sparta global/github/homework (Sam)`
`$ git push`



`Sam Morris@DESKTOP-EMUTIU5 MINGW64 ~/desktop/sparta global/github/homework (Sam)`
`$ git checkout main`

git checkout main - changes you back to the origin branch

`Sam Morris@DESKTOP-EMUTIU5 MINGW64 ~/desktop/sparta global/github/homework (main)`
`$ git merge Sam`

git merge - merges the branch back into the main branch with changes to the file

`Sam Morris@DESKTOP-EMUTIU5 MINGW64 ~/desktop/sparta global/github/homework (main)`
`$ git push`



`Sam Morris@DESKTOP-EMUTIU5 MINGW64 ~/desktop/sparta global/github/homework (main)`
`$ git branch -d Sam`

git branch -d - deletes the local branch from the repository

`Sam Morris@DESKTOP-EMUTIU5 MINGW64 ~/desktop/sparta global/github/homework (main)`
`$ git push origin --delete Sam`

git push origin --delete - deletes the branch from the remote repository 
