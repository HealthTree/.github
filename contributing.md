# How to contribute to HealthTree

## Fix bugs, implement features, tests

1. Go to (https://github.com/orgs/HealthTree/projects)
2. Pick any card from the **to do** list. High priority cards are on the top.
3. Clone the repository of the card.
4. Checkout the most recent version of **develop**
5. Create a new branch with the following naming convention: 

[ISSUE_NUMBER]/[feat|fix|maint|chore]/short-description 

Example: ```git checkout -b 123/feat/add-forget-password-button```

6. git commit --allow-empty -m "Branch Start"
6. Create a draft pr ```gh pr create --body "Resolves #59" --title "test gh integration" --project "HealthTree"```
