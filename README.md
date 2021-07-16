# Init project

hello world, this is my project

## Init Express project

First we have to install express-generator globally

```sh
npm install -g express-generator
```

Then generate new project by using these command line

 ```sh
express --view=ejs Appdev
```
 
>**NOTE**: Template engine is EJS and project's name is Appdev

Next, we will install all dependency package
```sh
npm install
```
## Setup Git and Github
First, Initialized empty Git repository in working directory
```sh
git init
```
Next, we will add all files from working tree to staging area
```sh
git add .
```
Next, we will check the all in staging area
```sh
git status
```
Next, we will create the first commit
```sh
git commit -m "Init project"
```
Next, we will connect to remote repository on github
```sh
git remote add origin https://github.com/dinhtrantienbao0409/appDev_project.git
```