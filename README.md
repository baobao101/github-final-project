# github-final-project
## My final project : Subversion Git CLI GitHub UI

A calculator that calculates simple interest given principal, annual rate of interest and time period in years.

Input:
   p, principal amount
   t, time period in years
   r, annual rate of interest
Output
   simple interest = p*t*r


## Scenario Part I
You recently got hired as a developer in a micro-finance startup with a mission to empower and provide opportunities for low income individuals. The core team currently uses Subversion (SVN) for managing code. They want to slowly move their code to Git. You are asked to host their sample code to calculate simple interest on GitHub in a new repository as the first step in this journey. You will not only host the script, but also follow best practices introduced in this course and create supporting documents for the open source project including a code of conduct, and contribution guidelines. Additionally, the repository should be available to the community under the Apache License 2.0.


### Task 1: Create a GitHub repository
- [ ] Create a new GitHub repository called "github-final-project" and make sure that it is public.
- [ ] Select the Add a README file and Choose a license check boxes. Pick Apache 2.0 License from the drop down.
- [ ] Click Create repository. Your repository is created and includes the README and LICENSE files. Now, you are ready to update your repository files to include useful information for your community.
- [ ] Save the URL of the repository in a Notepad to submit later for peer review.

### Task 2: Add a license file
- [ ] As part of Task 1, you picked a licence when creating the repository.
- [ ] Open the LICENSE.md file and check that its content are pointing to Apache License 2.0.

### Task 3: Update the README file

### Task 4: Add a code of conduct
- [ ] Add a new file named CODE_OF_CONDUCT.md to the root folder of the repository with the "Contributor Covenant" template.
- [ ] Go to your repositories homepage and check if the file has been created.

### Task 5: Add contribution guidelines
- [ ] Create a new file named CONTRIBUTING.md
- [ ] Commit the file into the main branch and check if it is listed on the homepage of the repository.

### Task 6: Host the script file
- [ ] Create a new file named simple-interest.sh in the root directory of the repository.
- [ ] Commit the file into the main branch.


## Scenario Part II
Congratulations on starting the journey with your company by creating an open-source Simple Interest Calculator bash script on GitHub. Your changes have been accepted and merged and the company has created a new global repository for the teams to collaborate. Other developers have contributed to this repository over time. Your team has found a mistake in one of the markdown files. You are asked to fork this repository and fix the mistake by using Git CLI in the provided lab environment and open a pull request (PR).


### Task 1: Fork the repository
- [ ] Fork the project's source repository.
- [ ] Save the URL of your forked repository in a notepad to submit later for peer review.

### Task 2: Fix the typo and merge with main
- [ ] Clone the forked repository in the lab environment.
- [ ] Create a branch named bug-fix-typo.
- [ ] Change the footer in the main README.md file
- [ ] Add the file with your fix and commit it with a meaningful message.
- [ ] Push your fix to the bug-fix-typo branch. In this step, you will need to generate a personal access token from GitHub.com to use as your password. Follow the instructions in the lab Generate GitHub personal access token.
- [ ] Switch to the main branch. Merge the bug-fix-typo branch back into your main branch. Take a screenshot showing the current branch and successful merge operation with the file that has changed. Save the screenshot as merge_branches.png or merge_branches.jpg.

### Task 3: Revert the typo and submit a pull request
- [ ] Check the content of README.md in the main branch
- [ ] Create a new branch named bug-fix-revert.
- [ ] Revert back the change you implemented in the previous task using the git revert command. The file should now read:
- [ ] Push the revert to your repository in the bug-fix-revert branch. Please ensure you use the personal access token that you generated on Github for your account as the password (and not your actual git password), when prompted.
- [ ] Go to the GitHub UI. Create a new pull request from the bug-fix-revert branch of your repository to the main branch of the original repository. This PR will be closed automatically. Note the URL of this PR in a notepad to submit later for peer review.

### Task 4: Check the status of your branches
- [ ] Navigate to the Branches section within the GitHub UI on your page.
- [ ] Within this section, you will find the branch names along with their current status.
- [ ] Make a note of the URL of this page in a notepad to submit during peer review.

### Checklist
After completing this part of the final project, you should have:

- [ ] The forked repository URL.
- [ ] The pull request URL.
- [ ] The screenshot showing the merge operation of bug-fix-typo into main named merge_branches in png of jpg format.
- [ ] The URL of the Branches page showing the branches of the repository and their status.
