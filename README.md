# CTS2852C - Project

1. [Team](#Team)
1. [Instructions](#Instructions)
1. [Requirements](#Requirements)
1. [Changes](#Changes)
1. [Projects](#Projects)
1. [Issues](#Issues)
1. [Discussions](#Discussions)

## Team

|Project #|Team Name|Date and Time|
| -- | -- | -- |
| Project #1 | Team 7  | 9/1/21 |

|#| Member Name |
|-| -- |
|1.| Elisa Turner |
|2.| Shayla Wolf|
|3.| Replace with full name |


## Instructions

After joining and then cloning the remote repository from GitHub to a local repository for this team project, complete the following steps:

1. Each team member is to set their user name and email using the `git config user.name "your user name"` and `git config user.email "your GitHub email"` commands. Check that the correct username and email is set using the `git config -l` command. This needs to be done each time the remote repository is cloned to a local repository.
1. One team member must create a branch named `develop` off the main branch and push the branch to the remote repository. Creation and updating of files for the team project cannot start until the `develop` branch has been pushed to the remote repository.
1. One team member must create a GitHub Project Board. See [Projects](#Projects) below.
1. One team member must update the Project #, Group Name and date/time in the **README.md** document using the steps to make [Changes](#Changes) below.
1. Each team member must add their name to the **README.md** document using the steps to make [Changes](#Changes) below.
1. Before any team member starts writing HTML, CSS or JavaScript code, create GitHub [Issues](#Issues) for each of the projects' different requirements.
1. Each team member must contribute HTML/CSS/JavaScript code to the team project. It is the responsibility of all team members to ensure that other team members contribute HTML/CSS/JavaScript code to the team project. Team members **must** contribute similar amounts of JavaScript code to the project.

## Requirements

The following requirements must be completed:

1. GitHub **Issues** and **Discussions** must be used to communicate with team members. External emails, texts or other communications will not be accepted for grading purposes.
1. See the appropriate **Group Project Requirements** page in D2L for the programming requirements of the project.
1. Once all project requirements are met:
    1. Ensure that all pull requests for merging to the `develop` branch have been merged and closed.
    1. Ensure that all completed Issues are closed.
    1. Ensure that all closed pull requests to the `develop` branch are merged to the `main` branch.
    1. When the project is ready for submission, one team member is to create a pull request from `develop` to `main` and assign it to another team member. The assigned team member will review and merge the `develop` branch into the `main` branch.
    1. One team member is to download the `main` branch of the remote repository (GitHub) and submit it before the due date and time to the appropriate **Group Project Assignment** dropbox in D2L. **Note**: The correct filename will have the repository name followed by `-main.zip`. Any team member can submit the team project. Multiple submissions to the dropbox are allowed by any team member and multiple team members can each submit to the dropbox. The last submission before the due date and time will be graded.

## Changes

1. A team member chooses an issue (either unassigned or already assigned to them) to work on and ensures they are assigned to the issue.
1. Move the issue from the **To do** column to the **In progress** column on the GitHub Project Board.
1. Check that the correct username and email is set using the `git config -l` command.
1. Switch to the `develop` branch and execute a `git pull` to get the latest code from the remote repository.
1. Create a new branch and switch to the new branch.
1. Add, modify and/or delete a file(s).
1. When a team member completes their changes:
    1. test the changes
    1. add the file(s) to the staging area
    1. commit the changes
    1. switch to the `develop` branch
    1. execute a `git pull` to get the latest code from the remote repository
    1. switch back to the new branch
    1. merge the `develop` branch to the new branch previously created and  resolve merge conflicts if there are any
        1. test that the code still works after the merge conflict is fixed
        1. add the file(s) fixed from the merge conflict to the staging area
        1. commit the fixed file(s)
    1. push the new branch to the remote repository
    1. close the GitHub Issue for the change
    1. create a pull request on the remote repository (GitHub) from the new branch to the `develop` branch
    1. assign the pull request to a fellow team member who will review the pull request and merge to the `develop` branch on the remote repository
1. Repeat these steps each time changes are to be made. **NOTE**: Ensure that a `git pull` is regularly executed while checked out on the `develop` branch to get any pull requests that have been merged to the `develop` branch.

## Projects

### Create a project

1. When in the repository, select the `Projects` link.
1. Choose the `Create a project` button.
1. Enter a name for the project. e.g. Kanban
1. Select `Automated kanban` as the template.
1. Choose the `Create project` button.
1. Delete any automatically created notes so that the columns of the board are empty.

See [About project boards](https://docs.github.com/en/issues/organizing-your-work-with-project-boards/managing-project-boards/about-project-boards) for more help.

## Issues

### Open an Issue

1. In the repository, select the `Issues` tab.
1. Choose `New issue`.
1. Enter a `Title` for the issue.
1. Enter details in the `Write` tab. Use the `@` symbol in the comment to bring up a list of team members so that the issue can refer a team member or all members of the team.
1. From the **Projects** section, select a previously created project. See [Adding issues and pull requests to a project board](https://docs.github.com/en/issues/organizing-your-work-with-project-boards/tracking-work-with-project-boards/adding-issues-and-pull-requests-to-a-project-board) for more help.
1. Choose `Submit new issue`.

### Assign an Issue

1. In the repository, select the `Issues` tab.
1. Select the issue that needs to be assigned to one or more team members.
1. Choose the `Assignees` option.
1. Select up to 10 team members to add to the issue.

### Filter issues assigned to you

1. In the repository, select the `Issues` tab.
1. Choose the `Assignee` drop down.
1. Select your username from the list.

### Close an Issue

1. In the repository, select the `Issues` tab.
1. Select the issue that needs to assigned to one or more team members.
1. Enter closing details in the `Write` tab.
1. Choose `Close and comment`.

### Reopen a Closed an Issue

1. In the repository, select the `Issues` tab.
1. Ensure `Closed` issues are displayed.
1. Select the issue that needs to be reopened.
1. Enter reopening details in the `Write` tab.
1. Choose `Reopen issue`.

See [About issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues) for more help.

## Discussions

### Start a discussion

1. When in the repository, select the `Discussions` link. If the Discussions link is not shown, contact the professor and request that discussions be enabled for the repository.
1. Choose the `New discussion` button.
1. Select a category.
1. Enter a title for the discussion at the top of the page.
1. Enter details in the `Write` tab. Use Markdown if applicable.
1. To @ mention a team member, use the `@` symbol in the comment to bring up a list of organization members and choose a team member. **Note:** All team members in the organization are listed. Ensure that the correct team or team member is being @ mentioned.
1. Choose `Start discussion`.

### Reply to a discussion

1. When in the repository, select the `Discussions` link.
1. Select the title of the discussion to be replied to.
1. If replying to a comment in the discussion, enter details into the `Write a reply` field and then choose the `Reply` button.
1. If no previous comment or not replying to a comment, enter details in the `Write` tab. Use Markdown if applicable. Then choose the `Comment` button.

See [About team discussions](https://help.github.com/articles/about-team-discussions/) for more help.
