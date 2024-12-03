# testing
git steps: 

// to check whether there is any changes or not in the particular file or folder


/// start
step 1: stay in main branch
step 2: create new branch 
        git branch branchname
step 3: move to newly created branch
        git checkout branchname
// now you are ready to do anything

//after start
1. git status

step 2: add the changes files
2. git add .

step 3: commit the changes file
3. git commit -m "Mentioned git command steps"

step 4: push the branch code to remote main
4. git push -u origin branchname

//end 
1. move to main branch
    git checkout main
2. merge the pushed branch to main
    git merge branchname
3. push the whole merged code to remote
    git push  or git push -u origin main

// after end
to see all the changes 
stay in main branch
1. either cmd: git fetch 
Or git pull (best)


