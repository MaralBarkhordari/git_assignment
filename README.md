# Git Assignment - <MaralBarkhordari>

a. What is an issue?
Issues are used to track todos, bugs, feature requests, and more in a software project. As issues are created, they will appear in a searchable and filterable list. GitHub issues are an extremely useful tool for communicating decisions, ideas and problems that are project specific. They are an alternative to email or Slack that keep communication isolated to a particular project. Issues can be opened on GitHub and even when they're closed, they remain available. They're also accessible to all collaborators for transperancy. 



b. What is a pull request?
A pull request on GitHub is a tool that lets developers suggest modifications to a codebase. By creating a pull request, you're effectively requesting the maintainers of the repository to examine the changes and incorporate them into the main code. Pull requests enable teams to evaluate and discuss updates before they are merged, which helps maintain code quality and uniformity.
After forking a project, we can clone the repository to our local machine, make changes, and push them without affecting the original repository. Alternatively, we can clone the original repo, make changes, fork it afterward, and then merge our changes to the forked repo's master branch. If we want to collaborate and have our changes included in the original repository, we can create a pull request to propose merging our updates.



c. Describe the steps to open a pull request?
1.Go to the repository on GitHub.
2.There is a prompt that suggests comparing our recently pushed branch. Click on the "Compare & pull request" button.
3.To the pull request, we can see what branches and repos we're attempting to merge.
4.Provide a title for the pull request and a detailed description of the changes we’ve made. 
5.Click the "Create pull request" button to submit our pull request.



d. Describe the steps to add a collaborator to a repository (share write permissions)
1.Go to GitHub and log in to our account.
2.Navigate to the repository we want to add a collaborator to.
3.Go to repository settings
4.Click on "Add people" in manage access section.
5.Add a collaborator to intended repository by Searching their username, full name, or email
6.click the pencil icon next to the collaborator's name and select write permission.



e. What is the difference between git and GitHub? 
They have differences based on their purpose, location, usage and integration:
Purpose: Git is a version control system for tracking changes locally, while GitHub is a hosting platform that uses Git and offers additional collaboration and project management features.
Location: Git runs on your local machine, whereas GitHub is an online service accessed through the web.
Usage: Git manages code versions and collaboration on a local level; GitHub facilitates online collaboration, sharing, and project management.
Integration: GitHub leverages Git's capabilities and adds a user-friendly interface and collaborative features, making it popular for open-source and team-based development projects.
In short, Git is the tool for version control, while GitHub is a service for hosting Git repositories and facilitating collaboration online.



f. What does git diff do?
If we want to see more details of the changes that we've made, we can use the command git diff. git diff compares what is in our working directory to what is in our staging area. If we've made changes to our files without running git add , we'll see the comparison. If there are no differences, nothing will be shown.



g. What is the main branch?
In Git, the default branch is named master or main. When we first start making commits, we start at the master branch that automatically points to the last commit made. The main branch is the central place for stable production-ready code in a project, serving as the foundation for all development and deployment activities.



h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch? 
No, it's not a good idea to push changes directly to the main branch after the initial commit in a new repository. Instead, we should:
1.Create a Separate Branch and use that for new features or other changes. This helps keep the main branch stable and unaffected by ongoing development.
2.Work on our changes in the new branch and commit updates.
3.Submit a Pull Request to merge your branch into the main branch. This allows others to review and test the changes before they are integrated.
Using this workflow helps maintain the stability and quality of the codebase while making collaboration and project management more efficient.