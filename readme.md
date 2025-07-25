# Git Course

## First Step - Config USER and EMAIL

```bash
git config --global user.name "Luis Paulo"
git config --global user.email "franca.luiz.paulo.777@gmail.com"
```
## Second Step - Add all files

```bash
add . 
```

## Third Step - Commit Files

```bash
git commit -m "Title of my commit files"
```

## Fourth Step - Rename Master Branch

```bash
git branch -m main //Quando posicionado na própria branch (ramificação)
```

## Fifth Step - List all branchs

```bash
git branch 
```
## Sixth Step - Create a new branch

```bash
git branch mybranch
```
## Seventh Step - Move to a new branch

```bash
git checkout name_of_branch
``` 
## Eighth Step - Merge Branchs

```bash
git marge "branch name" //Mescla a branch atual com a informada 
```

## Nineth Step - Copy local repository to remote

```bash
git remote add origin https://github.com/lpf-developer/git_course.git
```

## Tenth - Show remote repository created

```bash
git remote
```
## Eleventh Step - Push local repository files to remote repository

```bash
git push -u origin main
```
