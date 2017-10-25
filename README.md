# Hello World
Follow this tutorial to create your first web application!

# Installations & Registrations
## Desktop Installations
- Google Chrome [Download here](https://www.google.com/chrome/browser/desktop/)
- Node.js LTS [Download here](https://nodejs.org/en/)
- Visual Studio Code [Download here](https://code.visualstudio.com/Download)
- Now.sh [Download here](https://zeit.co/download)

## Command Line Installations
Open the terminal:
- Mac - open Spotlight search and type `terminal` 
- Windows - press Start and type in the search bar `cmd` 

Type the following command:
```
npm install -g sails now heroku-cli git
```
This might take a while to install, wait until the process is finished.

## Registrations
- Now.sh [Signup here](https://zeit.co/login)
- Heroku [Signup here](https://signup.heroku.com/)

# Create your Code Directory (one time only)
- Open the terminal
- Go to your home directory (windows: `cd \` | mac: `cd ~`) 
- Create a new folder named Code (windows: `md Code` | mac: `mkdir Code`) 
- Enter into your new folder `cd Code`

# Create the HelloWorld Application
- In the `Code` directory, Generate the helloworld app. 
Type `sails new helloworld` (you can change 'helloworld' with any other app name)
- Navigate into the new generated app folder. Type `cd helloworld`
- Run the app. Type `sails lift`
- Open Chrome and navigate to [http://localhost:1337](http://localhost:1337) to see the app
 
# Make Some Modifications 
- Open Visual Studio Code
- Open the `helloworld` folder (File > Open)
- Click on the `views` folder in the left side bar and click on the `homepage.ejs` file
- Delete all the text in the file and instead write `Hello World` (or any other text you'd like).
- Save the file
- Refresh the browser to see the change

# Deploy your app
## Upload to heroku
- Open the terminal 
- if sails server is running (with the boat thing), press Ctrl+C to terminate it.
- In the `helloworld` directory, create a new app in Heroku. Type `git init && heroku create` (**first time only**)
- Deploy your app `git add . && git commit --no-edit --allow-empty-message && git push heroku master` (**every time you change the code**)
- Wait for the deployment to finish
- Open your app (the url will be written at the end under `remote:    https://[your-app-name].herokuapp.com/ deployed to Heroku`)

## Upload to Now.sh
- Open the terminal
- if sails server is running (with the boat thing), press Ctrl+C to terminate it.
- In the `helloworld` directory type the command `now` (enter your credentials if needed)
- Wait for the deployment to finish
- Open your app (the url will be written at the beginning under `Ready! https://[your-app-name].now.sh/ (copied to clipboard)`

# Hooray! You now have your first published website
