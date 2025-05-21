This is for Github Practice
Process:
    1. Initialize Git Repository Locally
        cd your-project-folder git init
        git remote add origin https://github.com/VarunChavda78/Github-Practice
    
    2. Add and Push Code
        git add .
        git commit -m "Initial commit"
        git push -u origin master  # or main

    3. Create Branches
        # Create dev branch
        git checkout -b dev
        git push origin dev

        # Create feature branch
        git checkout -b feature/some-feature
        git push origin feature/some-feature

        # Switch to main branch 
        git checkout main
    
    4. Create readme.md file in dev repo, after this, create pull request and merge to master branch

    5. Create Git Tags
        git tag v1.0
        git push origin v1.0

Challenges:
    first you push code to dev branch and after merge to master branch right,
    then checkout to master branch and update the code and whenever you push this code to master branch is give you rebase error,
        for solve this error you need to run this command
            git pull --rebase origin master
        It means, your are behind from their current commit, for this you need to get pull means run above command, it gives you current stage, and after run this code, continue to push our code
            git push origin master