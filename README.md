# Group 75
# restaurant-website


## How to Use Repo

```bash
git clone https://github.com/FullStackTorture/eatery-vanilla.git
cd eatery-vanilla
```

### Create a New Branch locally
I suggest creating a seprate branch from your main branch where all your work and changes you make will be stored. This will keep you main or master branch clean at all times, meaning that your main or master branch will always be similar to the original master.

```bash
git checkout -b updates # `-b` creates the branch if it does not exist give it a name of your choice
```

### Commit your changes
```bash
git status
git add .
git commit -m "your commit message"
git push origin updates # branch `updates` was created earlier