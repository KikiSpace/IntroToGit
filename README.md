# Team Collaboration Document
Github Source: 

Team Member: 

## Feature Development Documentation
### Creating a New Feature Branch
Whenever you start developing a new feature, create a new branch in the format name/featureName. For example: xinqizhang/updateTeamMemberName.

``` git checkout -b name/featureName ```

### Committing Your Progress
To maintain a clear history of your progress, commit your modifications frequently. For example, if you are working on the painting position part of a feature while at a cafe and you need to leave for an errand, you should commit your changes before leaving:

``` git commit -m "Finish morning work" ```

### Keeping Your Branch Updated
To ensure your branch is always up-to-date, pull from the main branch before making any progress. For example, if you notice an update on the main branch by another teammate, sync your code with the main branch. In your local branch, run:

``` git pull origin main ```

### Resolving Merge Conflicts
If there are conflicts, you will need to resolve them before you can continue. Here's how you can do it:
- Identify the Conflicted Files: Git will highlight which files have conflicts.
- Open the Conflicted Files: Use your text editor or IDE to open the files with conflicts. Look for conflict markers (e.g., <<<<<<<, =======, >>>>>>>).
- Resolve the Conflicts: Decide whether to keep your changes, the changes from the main branch, or a combination of both. Edit the file to resolve the conflict.
- Mark the Conflict as Resolved: After resolving the conflicts, stage the resolved files:
``` git add <fileName>```

- Complete the Merge: Once all conflicts are resolved and staged, complete the merge:
``` git commit```

### Making Sure Your Changes Are Good
Before merging your code into the main branch, ensure that your changes are tested and do not block other teammates' progress. Once your local changes are tested and verified, create a Pull Request (PR). Add all related teammates as reviewers to help monitor your changes. Good teammates should leave helpful comments and support in resolving potential conflicts. You can only merge your changes into the main branch after getting approval from everyone.By following these practices, you'll ensure a smooth and collaborative development process.
Steps:
- Test your branch change
- Create Pull Request on Github
- Add related teammates as reviewers
- Get feedback from reviewers
- Get approval from reviewers
- Merge your code to main branch

------------------------------------------------


### Sample Pull Request

#### Description:
This PR adds my name to our Team Collaboration Document. 

#### Changes:

Added my name: `yourname`
#### Testing:

no test needed
#### Checklist:

- [ ] I confirmed that my name is spelled correctly.
- [ ] I confirmed that this is my team.


#### Additional Notes:
Hey team, please help me review and approve my PR so I can merge it into the main branch.

