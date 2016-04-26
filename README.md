# Git Commands

## Clone a Repository
```
git clone <git url>
```

## Clone a Repository with branch
```
git clone <git url> -b <branch name>
```

## Update change to repository

- Add new file

```
git add
		<file_path>      path to file you want to add
		--all            add all new file
```

- Commit change

```
git commit -m <message> <file_path>       commit file change
git commit -am <message>                  commit all file change
```

- Push to repository

```
git push <origin> <branch>
```

## Git Tags

- Create new tag
```
git tag <tab_name>
git push --tags
```

- Remove tag
```
git tag -d <tag_name>
git push <origin> :refs/tags/<tag_name>
```

- Revert to old commit
```
git reset --hard <commit>
git reset --soft HEAD@{1}
git commit -m <message>
git push
git reset --hard
```
