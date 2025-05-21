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
