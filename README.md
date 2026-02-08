# PAF Lab one
```dash
mkdir git-lab
cd git-lab
git init
touch HelloWorld.html (create file)
```

## Staging Area

```dash
- git add HelloWorld.html (Add File to Staging Area)
- git add --all (Add ALL files at once (most common))
- git add \*.html (Add all files of a specific type)
- git add src/ (Add files inside a folder)
```

### Interactive mode (advanced but useful)

```dash
- git add -i
```

## Link Local Repo to GitHub
```dash
- git remote add origin https://github.com/username/git-lab.git
```
## Check connection
```dash
- git remote -v
```
## Push Code to GitHub
```dash
- git branch -M main
- git push -u origin main
```
