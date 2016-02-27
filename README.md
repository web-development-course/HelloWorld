# Hello World
Follow this tutorial to create your first web application!

# Installations & Registrations
- Google Chrome [Download here](https://www.google.com/chrome/browser/desktop/)
- Node.js LTS [Download here](https://nodejs.org/en/)
- Visual Studio Code [Download here](https://code.visualstudio.com/Download)
- GitHub [Signup here](https://github.com/join) & [Download here](https://desktop.github.com/)
- Heroku Toolbelt [Signup here](https://signup.heroku.com/login) & [Download here](https://toolbelt.heroku.com/")
 
# Create your Code Directory (one time only)
- Open Node.js command prompt (windows) or the terminal (mac)
- Go to your home directory (windows: `cd \` | mac: `cd ~`) 
- Create a new folder named Code (windows: `md Code` | mac: `mkdir Code`) 
- Enter into your new folder `cd Code`
- Install Sails.js `npm install -g sails`
- Open GitHub Desktop and login with your account

# Create the HelloWorld Application
- In the Code directory, Generate the helloworld app `sails new helloworld` (your can change 'helloworld' with any other app name)
- Navigate into the new generated app folder `cd helloworld`
- Run the app `sails lift`
- Open Chrome and navigate to localhost:1337 to see the app
 
# Make Some Modifications 
- Open Visual Studio Code
- Open the `helloworld` folder (File > Open)
- Click on the `views` folder and click on the `homepage.ejs` file
- Change the text `A brand new app` and change it to any text you want
- Save the file

# Connect to a Git Repository
- Open the `helloworld` folder in Visual Studio Code (if not already open)
- Click on the Git icon (third from the top on the left)
- Click `Initialize Git Repository` (if the button appears)
- Write a commit message and click the checkmark icon
- Go to [GitHub](http://github.com), login and create a new repository
- In the setup screen, copy the bottom two lines (under "..or push an existing repository from the command line")
- In the command prompt, in your app directory, paste these lines and click [Enter]
- In windows, paste this line as well `git config --global credential.helper wincred`
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
