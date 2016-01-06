# Hello World
Follow this tutorial to create your first web application!

# Installations
- Google Chrome (<a href="https://www.google.com/chrome/browser/desktop/" target="_blank">download</a>)
- Sublime Text (<a href="http://www.sublimetext.com/" target="_blank">download</a>)
- GitHub (<a href="https://github.com/join" target="_blank">signup</a> & <a href="https://desktop.github.com/" target="_blank">download</a>)
- Node.js v4.2.3 (<a href="https://nodejs.org/en/" target="_blank">download</a>)
- Heroku Toolbelt (<a href="https://signup.heroku.com/login" target="_blank">signup</a> & <a href="https://toolbelt.heroku.com/" target="_blank">download</a>)
 
# Create the Application
- Open Node.js command prompt (windows) or the terminal (mac)
- Create a new folder (e.g. "Code") and cd into it
- Install Sails.js by typing `npm install -g sails`
- Generate the app by typing `sails new helloworld`
- Navigate into the new generated folder `cd helloworld`
- Run the app `sails lift`
- Open Chrome and navigate to localhost:1337 to see the app
 
# Make Some Modifications
- Open Sublime Text
- Open the `helloworld` folder 
- Open the `views` folder and click on the `homepage.ejs` file
- Change the text `A brand new app` and change it to any text you want
- Save the file

# Connect to a Git Repository
- Open the GitHub desktop app, login with your account
- (Windows only) open the project directory in the command prompt and type `git init`
- Go to GitHub desktop and click the top left '+' sign
- Choose Add
- Select the HelloWorld folder
- Click 'Add Repository'
- Write a commit message (e.g. "First Commit") and click [Commit]
- Click [Publish] (in the top right corner) and publish to repository
- (Windows only) click [Sync] (in the top right corner)
- Go to github.com and make sure that the repository exists with all the code
 
# Connect to Heroku
- Login to http://heroku.com
- Click '+' to create a new app (in the top right corner)
- Give it a unique name
- In the 'Deploy' tab, connect it to your GitHub repository
- Click [Enable Automatic Deploys]
- Go to Manual Deploy and click [Deploy Branch]
- Wait for the deploy to finish and click [View App]

# Hooray! You now have your first published website
