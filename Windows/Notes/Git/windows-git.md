# Windows: Git

## Process

### Clone

### Single Commit

### New Branch

```Git
git checkout -b <branch_name>
```

```Git
git commit --allow-empty -m "<branch_name>"
```

### Commit Changes

___This requires the use of `git commit --alow-empty`.___ 

If you do not create an empty commit, you will add your changes to the last commit before you created your branch. This is difficult to recover from and will most likely require deleting your branch and redoing your work.

```Git
git add -A
```

```Git
git commit --amend --no-edit
```

### Pushing Changes

#### Initial Push

#### Subsequent Pushes

### Git Log

`what to look for`

### Backup a Single Branch

### Backup All Branches

## Alieases

### fixup

## PowerShell

### New-GitBranch

### Update-GitBranch

### Push-GitBranch

### Backup-GitBranch

-All