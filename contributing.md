# How to contribute to HealthTree

## Fix bugs, implement features

1. Go to (https://github.com/orgs/HealthTree/projects)
2. Pick any card from the **to do** list. High priority cards are on the top.
3. Clone the repository of the card.
4. Checkout the most recent version of **develop**
5. Create a new branch with the following naming convention: 

[ISSUE_NUMBER]/[feat|fix|maint|chore]/short-description 

Example: ```git checkout -b 123/feat/add-forget-password-button```

6. Start coding, commits should be small, atomic and descriptive. Read: (https://www.conventionalcommits.org/en/v1.0.0/)
7. After your first commit, create a draft pr and link it to the issue. Example using gh cli:

```gh pr create --body "Resolves #59" --title "add-forget-password-button" --project "HealthTree" --draft```
8. Continue working and always push new commits by the end of your work day.
9. Once you are done, change the description on the PR, mark it as ready for review.
10. If somebody requests changes, implement them.
11. Verify that all PR checks passed, if not, fix any issues.
12. Once all reviews and checks are passed merge your PR. If your PR completes an issue the merge commit should include the ```Closes #59```. 
