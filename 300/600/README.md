# 600 - Create the Pull Request

- Replace TARGET_BRANCH_NAME by the name of the branch you want the changes to be pulled to. Most likely the ```main``` branch.
- Replace SOURCE_BRANCH_NAME by the name of the branch you want to create the pull request for.
- Replace PULL_REQUEST_TITLE by the title you want to pull request to contain for clarification of the pull request. Make sure to surround the title by quotes ("").
- Replace PULL_REQUEST_BODY by the body you want to pull request to contain for clarification of the pull request. Make sure to surround the body by quotes ("").

```
$ gh pr create --base TARGET_BRANCH_NAME --head SOURCE_BRANCH_NAME --title "PULL_REQUEST_TITLE" --body "PULL_REQUEST_BODY"
```

For example:

```
$ gh pr create --base main --head feature/add-greeting --title "Add greeting to README" --body "This PR adds a greeting to the README file."
```
