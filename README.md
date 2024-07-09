# stale-issues-test

Testing how the label/remove stale issues GitHub Action works.

Created a test issues on 7/3/2024 at 3:24pm 

Created a test pull request on 7/3/2024 at 3:27pm

Set the number of days stale to 1 and days stale before close to 1.

Ran workflow on 7/3/2024 at 3:47pm 
- no labels or messages (expected)

Workflow ran as scheduled at 6:30pm PT (1:30 UCT) on 7/4/2024
-"stale" label added to issue and PR
- received emails notifying that labels were added
- ![image](https://github.com/liteWilliamDeForest/stale-issues-test/assets/173209408/470d176b-189d-4002-83d1-c77eade27ec8)
- ![image](https://github.com/liteWilliamDeForest/stale-issues-test/assets/173209408/e9a593a5-2600-4218-b892-50d7ed2df990)
- ![image](https://github.com/liteWilliamDeForest/stale-issues-test/assets/173209408/3dbc147b-4be9-4777-b0da-4aaece38ad03)


Ran workflow 7/6/2024 (10:21am)
- Both issue and PR were closed by the GitHib Actions bot
- Notification emails received
- Branch that PR originated from was deleted
- ![image](https://github.com/liteWilliamDeForest/stale-issues-test/assets/173209408/3c201af2-841d-43b6-8b6c-80c21895270e)
- ![image](https://github.com/liteWilliamDeForest/stale-issues-test/assets/173209408/a574d5d8-8046-404e-9554-03ab9aab68f4)
- ![image](https://github.com/liteWilliamDeForest/stale-issues-test/assets/173209408/8486074d-0334-45d4-a51b-ca42217c1e67)
- ![image](https://github.com/liteWilliamDeForest/stale-issues-test/assets/173209408/0df11d96-19d5-47ec-86a5-ca2008d99ffa)



### 7/7 Update: Re-doing issue and PR test to check that the PR and branch are automatically closed when the workflow is run on the schedule rather than manually
