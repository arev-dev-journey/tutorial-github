# Lesson 1: Git Basics
---
## Describe version control and distributed version control
- Version control allows developers or collaborators to track changes to plain text or source code files
- Facilitates collaboration in development
- Distributed version control, (Git), everyone can have a copy or clone of a repo, Rapid and asynchronous
## Describe Git
- Open source version control software, VCS, created by Linus Torvalds 
## Describe GitHub
- Comprehensive hybrid cloud development platform, facilitating project management, issue tracking, code review, and CI/CD
- Users enjoy a robust AI-enhanced SDLC
- Access methods: REST API, web UI, mobile app, gh CLI
## Compare Git and GitHub
- Git is distributed system for handling version control, 100% free and open-source
- GitHub is platform that enhances Git with collaboration features
- Proprietary, closed-source software 
- Free open source software (GitHub CLI)
# Lesson 2: GitHub Basics
---
## Describe a Git repository
- A repo is a storage space for project files and version history
- Supports collaboration by tracking every text change
- 3 repo visibilities: public, internal, private
## Describe a commit
- A commit is a snapshot of your project at a specific point in time
- Includes a message describing what has changed and why
- Commits help with tracking history, enabling devs to roll back in time
- Every commit has a unique hash to track specific changes
- Standard is to use present tense
## Describe branching
- Allow developers to work on different features, bug fixes, or experiments independently from the main codebase
- Default branch is called main or master
- Create a new branch to isolate changes and prevent overwrites
- Helps avoid disruption in the main branch while allowing expermimentation
## Define a remote
- A remote is your version of your project hosted on GitHub
- Local repo is your copy on your machine, and remotes help synchronize with other team members
- **origin**: the default name for your GitHub remote when you clone a repo
- **upstream**: Used when your repository is a fork. It refers to the original repo from which your fork was made
- Common operations, git push, git pull, best practice; allows pull before you push
- Add a remote repo, git remote add https://github.com/user-name/repo.git
## Describe the GitHub flow
- A lightweight, branch-based workflow to streamline collaboration
- Key steps: Create a branch, Commit, changes, Open a pull request (PR), team members can review and discuss PR
- After approval, the branch is merged into the main branch
- The main branch is ready for deployment
# Lesson 3: GitHub Entities
---
## Describe the different GitHub acounts
- **Personal Accounts**: Individual users, free and paid plans, access to public and private repos
- **Organizations**: Teams and companies, Shared account by a separate GitHub entity, centralized management, advanced security features, billing and invoicing
## Describe GitHub's products for personal accounts
- **GitHub Free**: Public repos, limited private repos, basic collab tools
- **GitHub Pro**: Unlimited private repos, advanced collab tools, code review features
- **GitHub Team**: All feats of pro, plus team management tools and organization insights
## Describe GitHub's products for organization accounts
- **GitHub Team**: Same feats as personal plan, plus organization-wide management
- **GitHub Enterprise Cloud**: Advanced security and compliance, self-hosted runners, dedicated support
- **GitHub Enterprise Server**: On-premises deployment, full control over data and infrastructure
## Describe user profile features
- **Profile picture and bio**: Personalize your profile
- **Pinned Repositories**: Showcase your best work
- **Contributions graph**: Visualize your activity
- **Achievements**: Highlight your accomplishments
## Describe GitHub enterprise's deployment options
- **GitHub Enterprise** is the overall product name
- **GitHub Enterprise Cloud**: Hosted on GitHub's infrastructure, easy setup and maintanence, Called GHEC
- **GitHub Enterprise Server**: Deployed on your own servers, full control over data and security, Called GHES, you can deploy in a cloud
# Lesson 4: GitHub Markdown
---
## Describe markdown
- Lightweight markup language
- Plain-text formatting syntax
- Easy to read and write
- Renders to HTML
- Extends standard Markdown with a few key features thaht enhance its functionality with the GH ecosystem
- Ex. @, autoconvert URLs and email addrs into links
- `code` fencing
## Identify GitHub basic formatting syntax
- **Headers**: #, ##, ###
- **Emphasis**: _italics_, **bold**
- **Lists**: -, 1
- **Links**: [link text](URL)
- **Images**: ![alt text](image URL)
## Identify the text formatting toolbar on issue and pull request comments
- Located in **Issue** and **Pull Request**comment boxes
- Provides visual buttons for common formatting
- Can toggle between visual editor and Markdown code
## Explain where to find and use slash commands
- Type / to trigger
- Quick access to formatting and actions
- Available in issues, PRs, and discussion
- /label
- /assign
- /close
# Lesson 5: GitHub Desktop
---
## Explain the difference between GitHub desktop and GitHub.com

## Describe the available features with GitHub desktop

## Describe the available features with GitHub mobile

## Explain how to manage notifications through the GitHub Mobile app

# Lesson 6: Maintain GitHub Repositories
---
## Explain how to create a new repository

## Describe the components of a good README and the recommended repository files

## Explain basic repository navigation

## Describe repository templates

## Describe the different features to maintaining a repository

# Lesson 7: Manage GitHub Repositories
---
## Describe how to clone a repository

## Describe how to create a new branch

## Explain how to add files to a repository

## Explain how to save a repository with stars

## Explain feature previews

## Identify how to view repository insights

# Lesson 8: Manage GitHub Issues
---
## Describe how to create an issue

## Describe the difference between an issue, discussion, and pull request

## Describe how to link a PR to an issue

## Explain how to create a branch from an issue

## Identify how to assign issues

# Lesson 9: Master GitHub Issues
---
## Explain basic issue management 

## Describe how to search and filter issues

## Explain how to use keywords in issues

## Describe how to pin an issue

## Explain the difference between issue templates and issue forms

# Lesson 10: Work with Pull Requests
---
## Describe a pull request

## Explain how to create a new pull request

## Describe the base and compare branches in a pull request

## Describe draft pull requests

## Explain the relationship of commits on a pull request

## Describe the purpose of the pull request tabs

# Lesson 11: Master Pull Requests
---
## Explain the different pull request statuses

## Identify how to link Activity within a pull request

## Recognize how to comment on a postes link to a line or lines of code from a file

## Describe code review with a CODEOWNERS file

## Explain the different options for providing a code review on a pull request

# Lesson 12: Administer GitHub Discussions
---
## Describe the difference between discussions and issues

## Explain the options available with discussions

## Recognize how to pin a discussion

## Identify how to mark a comment as an answer to a discussion

## Explain how to convert a discussion to an issue

# Lesson 13: Manage GitHub Notifications
---
## Explain how to subscribe to a notification thread

## Describe how to find threads where you are
- Mentioned

## Identify the notification filtering options
- Based on various criteria

## Explain the different notification configuration options
- Participating and @mentions, All Activity, Ignore, Custom
- GitHub settings => Notifications => 

# Lesson 14: Use Gists, Wikis, and GitHub Pages
## Explain how to create a GitHub gist

## Describe how to fork and clone a gist

## Explain GitHub Wiki Pages

## Describe how to create, edit, and delete wiki pages

## Explain the visibility of wiki pages
- Public
- Private
## Describe GitHub Pages

# Lesson 15: Implement GitHub Actions
---
## Describe GitHub Actions

## Explain where you can use GitHub Actions with GitHub

## Explain where you can find existing GitHub Actions

# Lesson 16: Coding with GitHub Copilot
---
## Describe GitHub Copilot

## Get started using GitHub Copilot

## Describe the difference between GitHub Copilot for individuals and GitHub Copilot for business

# Lesson 17: Work with GitHub Codespaces
---
## Describe GitHub codespaces

## Start a GitHub Codespace

## Describe the codespace lifestyle

## Describe the differnet customizations you can personalize with GitHub codespaces

# Lesson 18: Master GitHub Codespaces
---
## Recognize how to add and configure dev containers

## Explain how to use the github.dev editor

## Explain the differences between the github.dev editor and a GitHub codespace

## Identify how to share a deep link to a GitHub codespace

# Lesson 19: Get Started with GitHub Projects
---
## Describe GitHub Projects

## Explain the layout options for projects

## Describe the configuration options for projects

## Explain the use of labels

## Explain the use of milestones

## Explain the difference between projects and projects classic

# Lesson 20: Work with GitHub Projects
---
## Explain how to create, edit, and delete saved replies

## Describe the benefits of using a saved reply

## Recognize how to add assignees to issues and pull requests

## Describe how to use and create template repositories

## Explain how to use project workflows

## Describe project insights

# Lesson 21: Administer Authentication and Security
---
## Explain how to secure you account with 2FA

## Describe the different access permissions

## Explain enterprise managed users

# Lesson 22: Manage GitHub Repositories
---
## Explain how to enable and disable features
## Recognize repository permissions levels
## Identify the options for repository visibility
## Explain the repository privacy setting option

# Lesson 23: Manage GitHub Organizations
---
## Describe members, teams, and roles in a GitHub organization
## Explain how to manage collaborators
## Explain how to manage organization settings
## Describe the main features and options in the security tab
## Define repository insights

# Lesson 24: Integrate with the Open Source Community
---
## Describe open source
## Describe how GitHub advances open source projects
## Describe GitHub sponsors
## Explain how to follow organizations
## Identify how to follow people 
## Describe the GitHub Marketplace and its purpose

# Lesson 25: Apply the Benefits of Open Source
---
## Describe InnerSource
## Identify the difference between innersource and open source
## Describe forking
## Describe the components of a discoverable repository
## Describe when to use issue templates
## Describe when to use issue templates
## Describe when to use pull request templates
