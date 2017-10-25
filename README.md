# Hello World
Follow this tutorial to create your first web application!

# Installations & Registrations
## Desktop Installations
- Google Chrome [Download here](https://www.google.com/chrome/browser/desktop/)
- Node.js LTS [Download here](https://nodejs.org/en/)
- Visual Studio Code [Download here](https://code.visualstudio.com/Download)
- Now.sh [Download here](https://zeit.co/download) | [Signup here](https://zeit.co/login)
- Heroku [Signup here](https://signup.heroku.com/)

## Command Line Installations
To install in the command line, open the command prompt (windows) or the terminal (mac) and type
```
npm install -g sails now heroku-cli git
```
This might take a while to install

# Create your Code Directory (one time only)
- Open the command prompt (windows) or the terminal (mac)
- Go to your home directory (windows: `cd \` | mac: `cd ~`) 
- Create a new folder named Code (windows: `md Code` | mac: `mkdir Code`) 
- Enter into your new folder `cd Code`

# Create the HelloWorld Application
- In the Code directory, Generate the helloworld app `sails new helloworld` (your can change 'helloworld' with any other app name)
- Navigate into the new generated app folder `cd helloworld`
- Run the app `sails lift`
- Open Chrome and navigate to [your localhost](http://localhost:1337) to see the app
 
# Make Some Modifications 
- Open Visual Studio Code
- Open the `helloworld` folder (File > Open)
- Click on the `views` folder and click on the `homepage.ejs` file
- Change the text `A brand new app` and change it to any text you want
- Save the file
- Refresh the browser to see the change

# Deploy your app
## Upload to heroku
- In the `HelloWorld` directory, create a new app in Heroku `git init && heroku create` (copy and save the new app url)
- Deploy your app `git add . && git commit --no-edit --allow-empty-message && git push heroku master`
- Wait for the deployment to finish

## Upload to Now.sh
- In the `HelloWorld` directory type the command `now` (enter your credentials if needed)
- Wait for the deployment to finish

# Hooray! You now have your first published website
