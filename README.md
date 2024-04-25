# Git Workshop Task: Update Attendee List

## Objective
This task is designed to help you practice basic Git commands by adding your name to an attendee list on an HTML page, creating a new branch, and then raising a pull request to merge this branch into the `master` branch.

## Instructions

### Setup
1. Fork this repository to your GitHub account.
2. Clone your forked repository to your local machine:
   ```bash
   git clone https://github.com/jslovers/demo-workshop-may-24.git
   ```
3. Navigate into the cloned directory:
   ```bash
   cd demo-workshop-may-24
   ```

### Task
1. Create a new branch for your changes:
   ```bash
   git checkout -b add-my-name-YOURNAME
   ```
2. Open the `index.html` file located in the root directory.
3. Find the `<ul>` tag for attendees.
4. Add a new `<li>` element with your name:
   ```html
   <li>Your Name</li>
   ```
5. Save your changes.

### Committing Changes
1. Add your changes to the staging area:
   ```bash
   git add index.html
   ```
2. Commit your changes with a descriptive message:
   ```bash
   git commit -m "Add <Your-Name> to attendee list"
   ```

### Pushing Changes
1. Push your changes to the new branch on your fork:
   ```bash
   git push origin add-my-name
   ```

### Raising a Pull Request
1. Go to your fork on GitHub.
2. You'll see a prompt to "Compare & pull request" for your newly pushed branch. Click it.
3. Ensure the base repository is set to the original repository and the base branch to `master`.
4. Confirm your changes and then click **'Create Pull Request'**.

## Conclusion
After completing this task, you will have successfully practiced cloning a repository, creating a new branch, making changes, committing them, pushing these changes back to GitHub, and initiating a pull request to merge your changes with the `master` branch. Good luck!
