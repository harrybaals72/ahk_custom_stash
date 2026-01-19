To sync changes from *other branch* add it with: 
```
git remote add upstream <git URL here>
```
To fetch and merge run:
```
# Get the latest data from the original
git fetch upstream

# Merge the original's main branch into your current branch
git merge upstream/main

# Push the combined code back to your private GitHub repo
git push origin main
```
