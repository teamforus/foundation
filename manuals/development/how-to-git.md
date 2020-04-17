### How to use git to get your features released faster to production

Using GIT to its full potential is a major factor in how we can release faster.

```
git checkout origin/master
git status # check if same as master; if any files changed check .gitignore if they can be ignored or git reset --hard origin/master && git pull
git checkout -b feature.* # or bugfix.name-of-issue.#45 
```

When finished make a draft pull request to develop
```
git add . 
git commit -m "teamforus/forus#45 fixed - WIP approved provider flow"
git push
hub pull-request -b develop -m "fixes teamfours/forus#45 - WIP approved provider flow" -r maxvisser -a maxvisser
```

## MAJOR CHANGES

Some features are major changes and need alot of code to be restructered/rewritten. These features are first started as a feature branch from master but can be added to a develop branch.
A develop branch main purpose is to avoid merge conflicts with these major changes. Only working branches are merged into develop (reviewed by Max). 
A developer (@dev-rminds, @aghimpu, @danieltcacenco) can decide that for a specific feature its better to base it from the develop branch as on this branch contains these major changes.
Consult issue creator about this if you are planning to base your branch from develop and why you think its necesarry.

```
git checkout origin/develop
git status # check if same as develop
git checkout -b feature.* # or bugfix.name-of-epic.name-of-issue-#45 
```

When finished make a draft pull request to develop
```
git add . 
git commit -m "teamforus/forus#45 fixed - WIP approved provider flow"
git push
hub pull-request -b develop -m "fixes teamfours/forus#45 - WIP approved provider flow" -r maxvisser -a maxvisser
```

## install Github hub
https://hub.github.com/
