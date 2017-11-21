# ReduxSimpleStarter

Personal notes:
- clone clean copy of ReduxSimpleStarter and name it
- cleanup and get ready for hosting:
  - package.json: script: add "webpack":"webpack"
  - .gitignore -> delete bundle.js

  - IN CODE:
    - delete leading '/' in script for style.css (top) and bundle.js (bottom)

- *** EVERY TIME YOU SAVE YOUR CODE, RUN:
  - npm run webpack

- create new repository in github
- in terminal:
  - git init
  - git add .
  - git commit -m "First commit"
  - git remote set-url origin https://github.com/gdevany/CityTempEtc.git  <-copy paste this from github page of newly created new repository
  - git remote -v  <- to verify origin is correct
  - git push origin





Interested in learning [Redux](https://www.udemy.com/react-redux/)?

### Getting Started

There are two methods for getting started with this repo.

#### Familiar with Git?
Checkout this repo, install dependencies, then start the gulp process with the following:

```
> git clone https://github.com/StephenGrider/ReduxSimpleStarter.git
> cd ReduxSimpleStarter
> npm install
> npm start
```

#### Not Familiar with Git?
Click [here](https://github.com/StephenGrider/ReactStarter/releases) then download the .zip file.  Extract the contents of the zip file, then open your terminal, change to the project directory, and:

```
> npm install
> npm start
```
