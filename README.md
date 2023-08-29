# Gitlab Git Certification

## Chapter 3: GitLab Components and Workflows

### Section: Development workflow in Gitlab

A GitFlow is a set of instructions or guidelines that prescribe how to utilize Git effectively and efficiently in order to achieve work in a consistent and productive way. GitLab Flow creates a seamless approach to software development by integrating a Git workflow with an issue tracking system.

#### Basic Git Workflow with GitLab

GitLab is based on Git and provides your team with a central repository. You use git locally on your own system to create and update code, share your changes with your team, and see your team’s changes by using git commands to push, fetch, and merge work. 

#### GitLab Workflow
 - Create an issue
 - Create a merge request
 - Commit changes
 - Ci Pipeline runs
 - Security checks
 - Review app
 - Discussion, code & security reviews
 - Approve changes
 - Merge, issue closed
 - CD Pipeline runs
 - Monitor the app

#### The gitlab flow: a simple workflow

Git is the standard. A GitFlow is a set of instructions or guidelines that prescribe how to utilize Git effectively and efficiently in order to achieve work in a consistent and productive way. 

Gitlab Flow creates a seamless approach to software development by integrating a Git workflow with an issue tracking system.

all features and fixes go to the main branch while enabling production and stable branches

- Branches die once merged
- addresses  multiple environments, releases, and integrations
- additional branches to our feature branches, that are ephemeral and lightweight.

#### Environment branches
- Master is in a staging state.
- Merge request from master to pre-production branch
- Merge request from pre-production to production branch


#### Release branches
- Only for releasing versioned software.
- Each branch is a minor version.
- Master works as staging.
- A release branches out from a commit and gets deployed.
- If patches need to be applied, they can be cherry-picked from master.
- New version? Branch out further down the road.

Complement with video:
https://www.youtube.com/watch?v=7lgGEXpsflI&ab_channel=LambdaTest

#### Branching Tips and Tricks.
There are some cases that you may want to hold a master and production branch. For example, when deployments are done in some window, or their timing need to be controlled.

#### Lesson check

### Section: GitLab components

#### GitLab Workflow components

- Project === repository
  - The core building block where work is organized, managed, tracked and delivered to help the team to collaborate and plan work in the form of issues.	 
- Group === project
  - A collection of projects and/or other groups. They are like folders.
- Issue === story, Narrative, Ticket
  - An issue is part of a project. It is the fundamental planning object where the team documents the use case in the description, discusses the approach, estimates the size/effort (issue weight), tracks actual time/effort, assigns work, and tracks progress.	
- Epic === initiatives, themes
  - A collection of related issues across different groups and projects to help organize by theme
- Merge request === pull request
- Milestone === sprint, iteration
  - The linkage between the issue and the actual code changes. Captures the design, implementation details (code changes), discussions (code reviews), approvals, testing (CI Pipeline), and security scans.
- Labels === tags
  - Used to tag and track work for a project or group and associate issues with different initiatives
- Board === kanban
  - A visual listing of projects and issues useful for teams to manage their backlog of work, prioritize items, and move issues to the team or specific stage in the project.
- Milestone === release
  - A sprint or deliverable(s), helping you organize code, issues, and merge requests into a cohesive group
- Roadmap
  - A visual representation of various epics for the group
- 
