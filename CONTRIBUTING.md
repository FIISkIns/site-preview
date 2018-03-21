# How to contribute to the project

Here is a list of steps a member of the team has to follow in order to contribute:

1. Make a local copy of the repository, using the git clone command.

2. Add a new branch to the local repository.

3. Modify the existent files correspondingly, or add new files.

4. After verifying that all the changes are valid, encapsulate them in a commit,
   choosing a clear and relevant message describing the changes and their role
   in the project.

5. Using the git push command, push the local changes onto the repository.

6. Open a pull request having the master branch as master.

7. Get approval from at least one member of the team, or repeat from step 3 in
   accordance to requests or comments from the other team members.

After merging the pull request, the member can delete the branch and start from
step 2 in order to improve the project's functionality.

## Automated tests

When opening a pull requests, all files in it are subjected to automated tests.
The tests are verifying the consistency of the code, the HTML5 validity and the
CSS validity. The tests will take about a minute to run, and their result will
affect the status of the pull request. A pull request containing files that
didn't pass the tests can't receive approval from the other team members.
