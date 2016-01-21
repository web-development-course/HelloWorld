# Hello World
Follow this tutorial to create your first web application!

# Installations
- Google Chrome (<a href="https://www.google.com/chrome/browser/desktop/" target="_blank">download</a>)
- Sublime Text (<a href="http://www.sublimetext.com/" target="_blank">download</a>)
- GitHub (<a href="https://github.com/join" target="_blank">signup</a> & <a href="https://desktop.github.com/" target="_blank">download</a>)
- Node.js v4.2.3 (<a href="https://nodejs.org/en/" target="_blank">download</a>)
- Heroku Toolbelt (<a href="https://signup.heroku.com/login" target="_blank">signup</a> & <a href="https://toolbelt.heroku.com/" target="_blank">download</a>)
 
# Create your Code Directory (one time only)
- Open Node.js command prompt (windows) or the terminal (mac)
- Create a new folder named `Code` (windows: `md Code`, mac: `mkdir Code`) 
- Enter into your new folder `cd Code`
- Install Sails.js `npm install -g sails`

# Create the Application
- In the Code directory, Generate the app `sails new helloworld`
- Navigate into the new generated app folder `cd helloworld`
- Run the app `sails lift`
- Open Chrome and navigate to localhost:1337 to see the app
 
# Make Some Modifications 
- Open Visual Studio Code
- Open the `helloworld` folder 
- Open the `views` folder and click on the `homepage.ejs` file
- Change the text `A brand new app` and change it to any text you want
- Save the file

# Connect to a Git Repository
- In Visual Studio Code, click on the Git icon (third from the top on the left)
- Click `Initialize Git Repository`
- Write a commit message and click the checkmark icon
- Go to [GitHub](http://github.com), login and create a new repository
- In the setup screen, copy the bottom two lines (..or push an existing repository from the command line)
- In the command prompt, in your app directory, paste these lines and click [Enter]
- In Visual Studio Code, in the Git section, click on the three dots (top left) and choose `Publish` or `Sync` (whichever's available)
- Go back to the repository on [GitHub](http://github.com), and make sure that the repository exists with all the code

# Connect to Heroku
- Login to [Heroku](http://heroku.com)
- Click '+' to create a new app (in the top right corner)
- Give it a unique name
- In the 'Deploy' tab, connect it to your GitHub repository
- Click [Enable Automatic Deploys]
- Go to Manual Deploy and click [Deploy Branch]
- Wait for the deploy to finish and click [View App]

# Hooray! You now have your first published website
