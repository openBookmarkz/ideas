# Contributing Guidelines

- [Getting Started](#getting-started)
    - [Project Setup](#project-setup)
    - [Adding to the project]()
- [Make & Commit your Changes](#make--commit-your-changes)
    - [Submission Template](#submission-template)
- [Create a Pull Request (PR)](#create-a-pull-request-pr)


## Getting Started

Contributing to open source projects, like this one, can be a rewarding experience allowing participants to learn, teach, share and gain experience.

View openBookmarkz/ideas open [issues here](https://github.com/openBookmarkz/ideas/issues) and follow the instructions below to contribute to this project.


### Project Setup

1. Create a [Fork of this project](https://github.com/openBookmarkz/ideas/fork). This will create a copy of the original repository in your GitHub account that you own, allowing you to make changes without affecting the original repo.

    [![Create a fork gif](https://i.gyazo.com/627b749f3579b667764b2aa5bdb1d62e.gif)](https://gyazo.com/627b749f3579b667764b2aa5bdb1d62e)

2. Go to the forked repo in your GitHub (if the page hasn't automatically opened, you can find this in your repositories) and click the `Code` button. Choose HTTPS (or SSH if you have this setup) and copy the link.

    [![Image from Gyazo](https://i.gyazo.com/31267ab345a0953d8029e27ab99822a8.gif)](https://gyazo.com/31267ab345a0953d8029e27ab99822a8)

3. In your IDE, open a terminal/command line, and run the following command to clone your forked repo into the IDE:

   ```bash
   git clone <insert copied link from step 2 here>
   ```

4. Set the upstream (the original repo) by running the following command in the terminal/command line:

    ```bash
    git remote add upstream https://github.com/openBookmarkz/ideas.git
    ```

5. Confirm that the upstream has been correctly added by running `git remote -v` in the terminal/command line. This will then output two origin links and two upstream links. The origin links are used for pushing and fetching from your forked repo. The upstream are used to push and fetch from the original repo. You should see something similar to the example below:

    ```bash
    git remote -v

    origin  git@github.com:kera-cudmore/ideas.git (fetch)
    origin  git@github.com:kera-cudmore/ideas.git (push)
    upstream        https://github.com/openBookmarkz/ideas.git (fetch)
    upstream        https://github.com/openBookmarkz/ideas.git (push)   

    ```


4. Create a new branch to work on. In the terminal/command line run the following command: 

   ```bash
   git checkout -b <branchName/your-idea>
   ```

5. Tell Git to track this branch. In the terminal/command line run the following command:

    ```bash
    git push -u origin <branch name>
    ```

## Make & Commit your Changes

Once you are happy with your changes, you will want to commit the changes to your forked repo and then submit a pull request using the submission template back to the original repo. A Pull Request (PR) is how a contributor begins the process of merging their changes back into the original project.

1. Add, commit and push your changes to your forked repository: 

    ```bash
    git add <filename>
    git commit -m "<Commit message here>"
    git push
    ```


### Submission Template

Kindly utilize the [Submission Template](https://github.com/openBookmarkz/ideas/tree/main/ideaTemplate) as a reference for the submission of your idea.


## Create a Pull Request (PR)

1. In the [original repo](https://github.com/openBookmarkz/ideas) click the Pull Requests tab in the top menu.

    ![Pull Requests Top Menu](https://github.com/openBookmarkz/ideas/assets/92253071/eb7ff765-18ce-43fa-ad45-5073274a6402)


2. You should be able to see a yellow banner at the top of the screen with a green button that says `compare & pull request`. Clicking this button will start the Pull Request process.

    ![Create pull request button](https://github.com/openBookmarkz/ideas/assets/92253071/1d1870e8-10a7-4b22-b27c-1fe9ff2c6fa0)

3. This will open the pull request page where you can provide a comprehensive overview of your contribution using the pre-populated [Idea Template](https://github.com/openBookmarkz/ideas/tree/main/ideaTemplate). Please fill out the template with your contribution and [reference the issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue) (if applicable).

    
    ![Pull request page](https://github.com/openBookmarkz/ideas/assets/92253071/c1352683-bb73-4b63-814d-eefca4fb74c0)

4. Click the `Create pull request` button at the bottom of the form to submit your pull request.

3. The team will then review your contribution, provide feedback if necessary (you will be notified via email), and merge your contribution into the main project if it aligns with our goals and standards.
