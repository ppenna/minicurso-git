# Git Sheet Cheat

- [Branches](./git-sheet-cheat.md#branches)
- [Commits](./git-sheet-cheat.md#commits)
- [Patches](./git-sheet-cheat.md#patches)

## Branches

#### Create

```
git checkout -b <branch>
```

#### Delete Local

```
git branch -D <branch>
```

#### Delete Remote

```
git push --delete -u origin <branch>
```

#### Merge

```
git merge --no-ff <branch>
```

#### Push

```
git push -u origin <branch>
```

#### Rebase

```
git rebase -i <branch>
```

#### Switch

```
git checkout <branch>
```

## Commits

#### Create

```
git commit -m "message"
```

#### Edit

```
git commit --amend
```

#### Get

```
git pull
```

#### Stage Changes

```
git add --patch <files>
```

#### Undo Changes

```
git checkout --patch <files>
```

#### Unstage Changes

```
git reset <files>
```

## Patches

#### Apply

```
git apply -3 <patch>
```

#### Apply and Merge

```
git am -3 <patch>
```

#### Create

```
git format-patch -1 <commit>
```
