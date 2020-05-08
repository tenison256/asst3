# Github Deployment
## First cd into your project folder


```
cd /users/arzu/Desktop/asst3 
```

## Check by pwd command

## Initialized as git project
```
git init
```


## Connect your local project with remote repo
```
git remote add origin https://github.com/tenison256/asst3.git
```

## add all files in my project to git memory
```
git add .
```

## commit my all changes
```
git commit -m “Initialized git repo”
```


## send your code on live repo (push your code)
```
git push -u origin master
```


# Firebase Deployment
[Help Link](https://firebase.google.com/docs/hosting/)

[Quick Start](https://firebase.google.com/docs/hosting/quickstart)

- Create a `public` folder inside your root folder
- Move all content into public folder

```
firebase init
```
- Select to set up Hosting. (move down by `arrowkeys` and select by `space`)
- Select a Firebase project to connect to your local project directory.
- Specify a directory to use as your public root directory.
- ignore creating/replace index.html


```
firebase deploy
```


