# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
Give information to npm that allows it to identify the project as well as handle the project's dependencies.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
The package.json is located root directory of your project because it talks to all other files and the other files depend on it.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
vue.min.js
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
API
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
In the log drain and the dashboard.
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
You set remote for your project
heroku git:remote -a <YOUR PROJECT NAME>

Then you push changes to Heroku Master
git push heroku master

```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Branching allows developers to write code for a project in parallel.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Code review should happen after automated checks but before you commit those changes you made to the main repository branch.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merging Branches
```