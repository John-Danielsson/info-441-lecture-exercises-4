# info-441-lecture-exercises-4

## Part 1: Deploy a nodejs site to Heroku:
https://devcenter.heroku.com/articles/getting-started-with-nodejs  (Links to an external site.)
Download Heroku CLI
Choose a project folder
Make sure project folder is git repo
Run “heroku create”
Make sure your project has the following
Start defined in package.json, e.g., 
  "scripts": {
    "start": "node app.js"
  },
Your app listens to the port defined in an environment variable PORT
const PORT = process.env.PORT || 3000;
app.listen(PORT, () => {
  console.log('Example app listening at http://localhost:PORT')
})
Make sure everything committed with git
Deploy app: “git push heroku main”
Part 2
Get a copy of the express-starter project: https://github.com/info-441-au21/express-starter/ (Links to an external site.) and make a new API endpoint (it can just return text that shows you got the routing to work).

 

## Turn in the following:
Paste text or a screenshot (Windows instructions (Links to an external site.), Mac instructions (Links to an external site.)) from your console or terminal showing some of your work on the exercise. You don't have to prove you finished or did it right, we just want to see that you attempted
Answers to these two questions (one or two sentences):

What is something that you found interesting in this lecture or exercise set (or why nothing interesting)?
What was something that you found challenging in this lecture or exercise set (or why nothing challenging)?
