# autotrader-hackathon
Group repository for the AutoTrader hack.

## Best Practices
Always create a branch from the latest commit on **main** before writing any code. Ideally, you should be the only person working on a given branch. The following commands should do so:
```
git checkout main
git pull
git checkout -b <branch name>
```
Commit and push code changes to your branch regularly:
```
git add .
git commit -m "<message>"
git push
```
You might need to set upstream at one point, just do what Git tells you to.

Finally, you have to merge your changes into main, once all of your changes are pushed:
```
git checkout main
git merge <branch name>
```
If there are merge conflicts, ~~panic~~ resolve them :).